# dev-vault

An everything development library. Repos, tools, and open source projects I
use, have used, or want to use, collected so the good stuff never gets lost
in a bookmarks folder. The goal: level up design and development with tools
that actually earn their place.

Every entry carries keywords, so the whole vault is searchable with Ctrl-F
or grep: match on a tool name, a problem (`smooth-scroll`, `token-cost`),
or a stack (`rust`, `python`, `vanilla-js`).

## UI/UX

| Repo | What it is | Keywords |
| --- | --- | --- |
| [lenis](https://github.com/darkroomengineering/lenis) | Lightweight, robust smooth scroll. WebGL sync, parallax, buttery feel in a few lines. | `smooth-scroll` `parallax` `webgl` `vanilla-js` |
| [GSAP](https://github.com/greensock/GSAP) | The animation platform. ScrollTrigger alone is worth it. Every premium plugin now free, no license. | `animation` `scroll-trigger` `timeline` `text-effects` |
| [vanta](https://github.com/tengbao/vanta) | Animated 3D website backgrounds, three.js wrapped WebGL in about five lines of code. | `3d` `backgrounds` `three-js` `webgl` |
| [react-bits](https://github.com/DavidHDev/react-bits) | 130+ animated React components. Text effects, backgrounds, interactions. Great to port to vanilla too. | `react` `components` `text-effects` `animation` |
| [headroom.js](https://github.com/WickyNilliams/headroom.js) | Hide the header on scroll down, reveal on scroll up. Tiny, dependency free, does one thing well. | `header` `scroll` `navbar` `vanilla-js` |

## Claude Code and skills

| Repo | What it is | Keywords |
| --- | --- | --- |
| [skills](https://github.com/anthropics/skills) | Anthropic's official skills repo. frontend-design lives here. | `claude` `skills` `frontend-design` `official` |
| [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Curated list of Claude skills, resources, and tools for customizing Claude workflows. | `claude` `skills` `awesome-list` `curated` |
| [superpowers](https://github.com/obra/superpowers) | Skill marketplace for Claude Code: brainstorming, planning, TDD, debugging, and more. | `claude` `skills` `tdd` `planning` `marketplace` |
| [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | UI/UX ruleset skill that sharpens Claude's design taste before it writes any frontend. | `claude` `skills` `design-rules` `frontend` |
| [claude-reflect](https://github.com/BayramAnnakov/claude-reflect) | Self-learning for Claude Code: captures corrections and preferences, syncs them to CLAUDE.md. | `claude` `memory` `self-learning` `feedback` |
| [claude-mem](https://github.com/thedotmack/claude-mem) | Persistent memory for Claude Code sessions. Compresses context and carries knowledge across sessions. | `claude` `memory` `context` `persistence` |
| [ponytail](https://github.com/DietrichGebert/ponytail) | Makes your AI agent think like the laziest senior dev in the room. The best code is the code you never wrote. | `claude` `skills` `yagni` `minimalism` `anti-bloat` |
| [i-have-adhd](https://github.com/ayghri/i-have-adhd) | A skill to stop your coding agent from burying the answer. ADHD-friendly output. | `claude` `skills` `output-format` `adhd` `readability` |
| [adhd](https://github.com/uditakhourii/adhd) | Tree-of-thought skill for coding agents: fans out parallel divergent thoughts under different cognitive frames, scores, prunes traps, deepens survivors. Built on the Claude and Codex Agent SDK. | `claude` `skills` `tree-of-thought` `creativity` `agent-sdk` |
| [cwc-long-running-agents](https://github.com/anthropics/cwc-long-running-agents) | Anthropic's harness primitives for long-running agents: default-FAIL contracts, fresh-context evaluator, agent-maintained handoff, as readable hooks and a subagent. | `claude` `agents` `harness` `hooks` `long-running` `official` |

## Agents and LLM tooling

| Repo | What it is | Keywords |
| --- | --- | --- |
| [browser-harness](https://github.com/browser-use/browser-harness) | Self-healing browser harness that enables LLMs to complete any web task. | `agents` `browser-automation` `self-healing` `python` |
| [HyperAgents](https://github.com/facebookresearch/HyperAgents) | Self-referential, self-improving agents that can optimize for any computable task. | `agents` `self-improving` `research` `meta` |
| [nanoclaw](https://github.com/nanocoai/nanoclaw) | Lightweight OpenClaw alternative that runs in containers for security. Connects to WhatsApp, Telegram, Slack, Discord, Gmail. Memory and scheduled jobs built in. | `agents` `containers` `messaging` `typescript` `scheduled-jobs` |
| [lacp](https://github.com/0xNyk/lacp) | Local-first policy, evidence, memory, and recovery controls for Claude, Codex, Hermes, and other CLI coding agents. | `agents` `policy` `local-first` `safety` `recovery` |
| [rtk](https://github.com/rtk-ai/rtk) | CLI proxy that cuts LLM token consumption by 60 to 90 percent on common dev commands. Single Rust binary, zero dependencies. | `token-cost` `cli` `proxy` `rust` `optimization` |
| [gbrain](https://github.com/garrytan/gbrain) | Garry Tan's opinionated OpenClaw/Hermes agent brain. Running on my Mac mini as an always-on agent via Tailscale. | `agents` `agent-brain` `always-on` `typescript` |
| [openwhispr](https://github.com/OpenWhispr/openwhispr) | Voice-command AI agent beyond dictation: local Whisper or NVIDIA Parakeet, edits text in place, meeting transcription with on-device speaker ID, MCP server. Hotkey, talk, text lands at your cursor. No cloud unless you opt in. MIT. | `voice` `dictation` `speech-to-text` `local-first` `mcp` |
| [chopin](https://github.com/githubnext/chopin) | GitHub Next research prototype: people and repo-grounded agents co-author durable documents (plans, specs, RFCs, decision records). The agent reads the repo, proposes changes, and asks the team when code cannot settle a choice. Experimental, self-hosted. | `agents` `planning` `co-authoring` `specs` `github-next` |

## Knowledge graphs

| Repo | What it is | Keywords |
| --- | --- | --- |
| [utopia](https://github.com/deeplethe/utopia) | Open source enterprise world model as a Rust binary and Postgres: ingests PDFs, resolves entities, gives every fact a validity interval. Corrections close and link rather than overwrite. Reasoning in temporal Datalog. Apache-2.0. | `knowledge-graphs` `ontology` `bitemporal` `datalog` `rust` |
| [knowledge_graph](https://github.com/rahulnyk/knowledge_graph) | Converts any text corpus to a knowledge graph: chunks the document, asks a 7B model which concepts relate, renders a force-directed network with pyvis, ranks concepts via networkx degree and community detection. MIT. | `knowledge-graphs` `graph-rag` `llm` `pyvis` `python` |

## LLMs: training and inference

| Repo | What it is | Keywords |
| --- | --- | --- |
| [unsloth](https://github.com/unslothai/unsloth) | Local UI to run and train LLMs and diffusion models. GGUF, MLX, Qwen, DeepSeek, Gemma, FLUX and more. | `llm` `fine-tuning` `local` `training` `gguf` `mlx` |
| [airllm](https://github.com/lyogavin/airllm) | 70B model inference on a single 4GB GPU. | `llm` `inference` `low-vram` `optimization` `python` |

## Writing

| Repo | What it is | Keywords |
| --- | --- | --- |
| [no-ai-slop](https://github.com/petergyang/no-ai-slop) | Removes 20+ patterns of AI slop from any piece of writing. | `writing` `ai-slop` `editing` `python` |

## Terminal and systems

| Repo | What it is | Keywords |
| --- | --- | --- |
| [rmux](https://github.com/Helvesec/rmux) | Universal Rust multiplexer with a typed SDK. Drive any CLI or TUI app from code. Native on Linux, macOS, Windows. | `terminal` `multiplexer` `tui` `rust` `sdk` |

## Quant and finance

| Repo | What it is | Keywords |
| --- | --- | --- |
| [FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal) | Modern finance terminal: market analytics, investment research, and economic data tools for data-driven decisions. | `finance` `quant` `market-data` `terminal` `c++` |
| [nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | Production-grade Rust-native trading engine with a deterministic event-driven architecture. Backtest and live trade from the same strategy code. | `quant` `trading-engine` `backtesting` `event-driven` `rust` |
| [Kronos](https://github.com/shiyu-coder/Kronos) | A foundation model for the language of financial markets. | `quant` `foundation-model` `time-series` `ml` `python` |
| [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | Personal trading agent from HKU data science lab: describe intent, the agent trades. | `quant` `agents` `trading` `llm` `python` |
| [skfolio](https://github.com/skfolio/skfolio) | Portfolio optimization built on top of scikit-learn: risk models, allocation, cross-validation for portfolios. | `quant` `portfolio-optimization` `scikit-learn` `risk` `python` |

## Learning

| Resource | What it is | Keywords |
| --- | --- | --- |
| [ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | Learn it. Build it. Ship it for others. AI engineering fundamentals from the ground up. | `learning` `ai-engineering` `fundamentals` `python` |
| [Language Model Builder](https://languagemodelbuilder.com/) | Free Mac app that walks you through building a small language model from scratch: tokenizer, data, pre-training, fine-tuning, then chat with your own model. | `learning` `llm` `from-scratch` `mac-app` `fine-tuning` |
| [A GitHub profile that generates itself](https://agreeable-credit-859.notion.site/A-GitHub-profile-that-generates-itself-3abedfe9a65a81e4afc9daed90cb4e7e) | Guide to a self-generating profile README: ASCII portrait, stats drawn by your own repo from the GraphQL API, SMIL animation, no third-party widgets. Code at [andriidrok1/andriidrok1](https://github.com/andriidrok1/andriidrok1). | `github-profile` `readme` `svg` `smil` `self-generating` `guide` |

## Robotics

| Repo | What it is | Keywords |
| --- | --- | --- |
| [robotics-toolbox-python](https://github.com/petercorke/robotics-toolbox-python) | Peter Corke's robotics toolbox. Kinematics, dynamics, IK plus Jacobians, motion planning, localization and SLAM, 50+ robot models (Franka, UR, Kinova, Puma). Code written to be read, so you can open the implementation and learn. | `robotics` `kinematics` `dynamics` `slam` `python` `manipulators` |
| [Modern Robotics course](https://hades.mech.northwestern.edu/index.php/Modern_Robotics) | The Lynch and Park textbook free online, with the full video course: six courses from robot motion foundations through manipulation, wheeled mobile robots, and a capstone. Also on [Coursera](https://www.coursera.org/specializations/modernrobotics), reference code at [NxRLab/ModernRobotics](https://github.com/NxRLab/ModernRobotics). | `robotics` `course` `kinematics` `dynamics` `textbook` `free` |
| [MATLAB and Simulink Robotics Arena](https://www.youtube.com/playlist?list=PLn8PRpmsu08qVJayVibu8Yr0uYCwWkLVP) | MathWorks' free robotics education playlist on real platforms: navigation with encoders, obstacle detection with IR sensors, vision-based autonomy, motor tuning, virtual world simulation, driver vs autonomous control. | `robotics` `course` `matlab` `simulink` `sensors` `free` |

## Adding entries

One line per repo: link, what it does in plain words, and a handful of
lowercase keywords covering the problem it solves and the stack it runs on.
If a tool stops earning its place, it gets removed, not archived.
