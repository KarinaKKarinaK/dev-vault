# dev-vault

An everything development library. Repos, tools, and open source projects I
use, have used, or want to use, collected so the good stuff never gets lost
in a bookmarks folder. The goal: level up design and development with tools
that actually earn their place.

Every entry carries keywords, so the whole vault is searchable with Ctrl-F
or grep: match on a tool name, a problem (`smooth-scroll`, `token-cost`),
or a stack (`rust`, `python`, `vanilla-js`).

## LLMs: training and inference

| Repo | What it is | Keywords |
| --- | --- | --- |
| [unsloth](https://github.com/unslothai/unsloth) | Local UI to run and train LLMs and diffusion models. GGUF, MLX, Qwen, DeepSeek, Gemma, FLUX and more. | `llm` `fine-tuning` `local` `training` `gguf` `mlx` |
| [airllm](https://github.com/lyogavin/airllm) | 70B model inference on a single 4GB GPU. | `llm` `inference` `low-vram` `optimization` `python` |
| [minimind](https://github.com/jingyaogong/minimind) | Train a 64M-parameter LLM completely from scratch in about 2 hours. | `llm` `from-scratch` `training` `learning` `python` |

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
| [ruflo](https://github.com/ruvnet/ruflo) | The original agent harness: multi-agent swarms, autonomous workflow coordination, adaptive memory, federation, vector RAG. Integrates Claude Code, Codex, Hermes. | `agents` `swarms` `orchestration` `rag` `typescript` |
| [hermes-agent](https://github.com/nousresearch/hermes-agent) | Nous Research's agent that grows with you. | `agents` `hermes` `personal-agent` `python` |
| [openclaude](https://github.com/Gitlawb/openclaude) | Open source coding-agent CLI for cloud and local model providers. Runs anywhere, uses anything. | `agents` `coding-agent` `cli` `local-models` |
| [OmniRoute](https://github.com/diegosouzapw/OmniRoute) | Free MIT AI gateway: one endpoint, 352 providers, 1200+ models. Works with Claude Code, Codex, Cursor. Quota-aware auto-fallback, token compression, MCP/A2A. | `gateway` `routing` `models` `fallback` `token-cost` |
| [Scrapling](https://github.com/d4vinci/Scrapling) | Adaptive web scraping framework that handles everything from a single request to a full-scale crawl. | `scraping` `crawling` `data-collection` `python` |
| [hyperresearch](https://github.com/jordan-gibbs/hyperresearch) | Agent-driven research knowledge base: agents collect, search, and synthesize web research into a persistent, searchable wiki. | `agents` `research` `wiki` `knowledge-base` `python` |

## Robotics

| Repo | What it is | Keywords |
| --- | --- | --- |
| [robotics-toolbox-python](https://github.com/petercorke/robotics-toolbox-python) | Peter Corke's robotics toolbox. Kinematics, dynamics, IK plus Jacobians, motion planning, localization and SLAM, 50+ robot models (Franka, UR, Kinova, Puma). Code written to be read, so you can open the implementation and learn. | `robotics` `kinematics` `dynamics` `slam` `python` `manipulators` |
| [Modern Robotics course](https://hades.mech.northwestern.edu/index.php/Modern_Robotics) | The Lynch and Park textbook free online, with the full video course: six courses from robot motion foundations through manipulation, wheeled mobile robots, and a capstone. Also on [Coursera](https://www.coursera.org/specializations/modernrobotics), reference code at [NxRLab/ModernRobotics](https://github.com/NxRLab/ModernRobotics). | `robotics` `course` `kinematics` `dynamics` `textbook` `free` |
| [MATLAB and Simulink Robotics Arena](https://www.youtube.com/playlist?list=PLn8PRpmsu08qVJayVibu8Yr0uYCwWkLVP) | MathWorks' free robotics education playlist on real platforms: navigation with encoders, obstacle detection with IR sensors, vision-based autonomy, motor tuning, virtual world simulation, driver vs autonomous control. | `robotics` `course` `matlab` `simulink` `sensors` `free` |

## Claude Code and skills

| Repo | What it is | Keywords |
| --- | --- | --- |
| [skills](https://github.com/anthropics/skills) | Anthropic's official skills repo. frontend-design lives here. | `claude` `skills` `frontend-design` `official` |
| [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Curated list of Claude skills, resources, and tools for customizing Claude workflows. | `claude` `skills` `awesome-list` `curated` |
| [superpowers](https://github.com/obra/superpowers) | Skill marketplace for Claude Code: brainstorming, planning, TDD, debugging, and more. | `claude` `skills` `tdd` `planning` `marketplace` |
| [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | UI/UX ruleset skill that sharpens Claude's design taste before it writes any frontend. Install: [skills.sh](https://skills.sh/nextlevelbuilder/ui-ux-pro-max-skill). | `claude` `skills` `design-rules` `frontend` |
| [claude-reflect](https://github.com/BayramAnnakov/claude-reflect) | Self-learning for Claude Code: captures corrections and preferences, syncs them to CLAUDE.md. | `claude` `memory` `self-learning` `feedback` |
| [claude-mem](https://github.com/thedotmack/claude-mem) | Persistent memory for Claude Code sessions. Compresses context and carries knowledge across sessions. | `claude` `memory` `context` `persistence` |
| [ponytail](https://github.com/DietrichGebert/ponytail) | Makes your AI agent think like the laziest senior dev in the room. The best code is the code you never wrote. | `claude` `skills` `yagni` `minimalism` `anti-bloat` |
| [i-have-adhd](https://github.com/ayghri/i-have-adhd) | A skill to stop your coding agent from burying the answer. ADHD-friendly output. | `claude` `skills` `output-format` `adhd` `readability` |
| [adhd](https://github.com/uditakhourii/adhd) | Tree-of-thought skill for coding agents: fans out parallel divergent thoughts under different cognitive frames, scores, prunes traps, deepens survivors. Built on the Claude and Codex Agent SDK. | `claude` `skills` `tree-of-thought` `creativity` `agent-sdk` |
| [cwc-long-running-agents](https://github.com/anthropics/cwc-long-running-agents) | Anthropic's harness primitives for long-running agents: default-FAIL contracts, fresh-context evaluator, agent-maintained handoff, as readable hooks and a subagent. | `claude` `agents` `harness` `hooks` `long-running` `official` |
| [skills (Emil Kowalski)](https://github.com/emilkowalski/skills) | Agent skills for designers and engineers, from the maker of sonner and vaul. Taste as markdown. | `skills` `design` `animation` `taste` |
| [impeccable](https://github.com/pbakaus/impeccable) | The design language that makes your AI harness better at design. Running it as a skill in my setup. | `skills` `design` `harness` `frontend` |
| [taste-skill](https://github.com/leonxlnx/taste-skill) | Gives your AI good taste. Stops it from generating boring, generic slop. | `skills` `design` `taste` `anti-slop` |
| [academic-research-skills](https://github.com/imbad0202/academic-research-skills) | Academic research skills for Claude Code: research, write, review, revise, finalize. | `skills` `research` `academic` `writing` |
| [stop-slop](https://github.com/hardikpandya/stop-slop) | A skill file for removing AI tells from prose. Install: [skills.sh](https://skills.sh/hardikpandya/stop-slop). | `skills` `writing` `anti-slop` `prose` |
| [humanizer](https://github.com/blader/humanizer) | Agent skill that removes signs of AI-generated writing from text. Install: [skills.sh](https://skills.sh/blader/humanizer). | `skills` `writing` `anti-slop` `humanize` |
| [diagram-design](https://github.com/cathrynlavery/diagram-design) | 38 editorial diagram types for Claude Code, Codex, and Pi. Self-contained HTML plus SVG, no shadows, no Mermaid slop. Install: [skills.sh](https://skills.sh/cathrynlavery/diagram-design). | `skills` `diagrams` `svg` `editorial` |
| [frontend-slides](https://github.com/zarazhangrui/frontend-slides) | Beautiful slides on the web using a coding agent's frontend skills. Install: [skills.sh](https://skills.sh/zarazhangrui/frontend-slides). | `skills` `slides` `presentations` `frontend` |

## Knowledge graphs

| Repo | What it is | Keywords |
| --- | --- | --- |
| [utopia](https://github.com/deeplethe/utopia) | Open source enterprise world model as a Rust binary and Postgres: ingests PDFs, resolves entities, gives every fact a validity interval. Corrections close and link rather than overwrite. Reasoning in temporal Datalog. Apache-2.0. | `knowledge-graphs` `ontology` `bitemporal` `datalog` `rust` |
| [knowledge_graph](https://github.com/rahulnyk/knowledge_graph) | Converts any text corpus to a knowledge graph: chunks the document, asks a 7B model which concepts relate, renders a force-directed network with pyvis, ranks concepts via networkx degree and community detection. MIT. | `knowledge-graphs` `graph-rag` `llm` `pyvis` `python` |
| [graphify](https://github.com/Graphify-Labs/graphify) | Turns any codebase, with docs, SQL schemas, configs, and PDFs, into a queryable knowledge graph. A /graphify skill for Claude Code, Cursor, Codex: local deterministic AST parsing, every edge explained, no vector store. | `knowledge-graphs` `codebase` `skills` `ast` `python` |
| [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) | Graphs that teach over graphs that impress: turn any code into an interactive knowledge graph you can explore, search, and question. Works with Claude Code, Codex, Cursor, Gemini CLI. | `knowledge-graphs` `codebase` `skills` `visualization` `learning` |
| [SSTorytime](https://github.com/markburgess/SSTorytime) | Mark Burgess' semantic spacetime story graph database library over PostgreSQL. Knowledge as process-ordered narrative, from the author of promise theory. | `knowledge-graphs` `semantic-spacetime` `postgresql` `go` |

## Quant and finance

| Repo | What it is | Keywords |
| --- | --- | --- |
| [FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal) | Modern finance terminal: market analytics, investment research, and economic data tools for data-driven decisions. | `finance` `quant` `market-data` `terminal` `c++` |
| [nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | Production-grade Rust-native trading engine with a deterministic event-driven architecture. Backtest and live trade from the same strategy code. | `quant` `trading-engine` `backtesting` `event-driven` `rust` |
| [Kronos](https://github.com/shiyu-coder/Kronos) | A foundation model for the language of financial markets. | `quant` `foundation-model` `time-series` `ml` `python` |
| [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | Personal trading agent from HKU data science lab: describe intent, the agent trades. | `quant` `agents` `trading` `llm` `python` |
| [skfolio](https://github.com/skfolio/skfolio) | Portfolio optimization built on top of scikit-learn: risk models, allocation, cross-validation for portfolios. | `quant` `portfolio-optimization` `scikit-learn` `risk` `python` |
| [hummingbot](https://github.com/hummingbot/hummingbot) | Open source framework for building and deploying high-frequency crypto trading bots. | `quant` `crypto` `hft` `market-making` `python` |

## Learning

| Resource | What it is | Keywords |
| --- | --- | --- |
| [ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | Learn it. Build it. Ship it for others. AI engineering fundamentals from the ground up. | `learning` `ai-engineering` `fundamentals` `python` |
| [Language Model Builder](https://languagemodelbuilder.com/) | Free Mac app that walks you through building a small language model from scratch: tokenizer, data, pre-training, fine-tuning, then chat with your own model. | `learning` `llm` `from-scratch` `mac-app` `fine-tuning` |
| [A GitHub profile that generates itself](https://agreeable-credit-859.notion.site/A-GitHub-profile-that-generates-itself-3abedfe9a65a81e4afc9daed90cb4e7e) | Guide to a self-generating profile README: ASCII portrait, stats drawn by your own repo from the GraphQL API, SMIL animation, no third-party widgets. Code at [andriidrok1/andriidrok1](https://github.com/andriidrok1/andriidrok1). | `github-profile` `readme` `svg` `smil` `self-generating` `guide` |
| [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) | MIT's course on everything CS classes skip: shell, editors, git, debugging, profiling, security. Source at [missing-semester/missing-semester](https://github.com/missing-semester/missing-semester). | `learning` `cs-fundamentals` `shell` `git` `mit` `free` |
| [DeepMind x UCL Deep Learning Lectures](https://www.youtube.com/playlist?list=PLqYmG7hTraZDVH599EItlEWsUOsJbAodm) | The DeepMind x UCL 2021 deep learning lecture series on YouTube. Slides for the companion RL course at [yjavaherian/deepmind-x-ucl-rl](https://github.com/yjavaherian/deepmind-x-ucl-rl). | `learning` `deep-learning` `reinforcement-learning` `lectures` `deepmind` `free` |
| [OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | Open multi-agent interactive classroom from Tsinghua: an immersive, multi-agent learning experience in one click. | `learning` `multi-agent` `classroom` `typescript` |

## Terminal and systems

| Repo | What it is | Keywords |
| --- | --- | --- |
| [rmux](https://github.com/Helvesec/rmux) | Universal Rust multiplexer with a typed SDK. Drive any CLI or TUI app from code. Native on Linux, macOS, Windows. | `terminal` `multiplexer` `tui` `rust` `sdk` |
| [playwright-cli](https://github.com/microsoft/playwright-cli) | CLI for common Playwright actions: record and generate test code, inspect selectors, take screenshots. | `testing` `browser-automation` `cli` `screenshots` |
| [invidious](https://github.com/iv-org/invidious) | Alternative front-end to YouTube: lightweight, private, no ads or tracking. | `youtube` `privacy` `frontend` `self-hosted` |

## macOS

| Repo | What it is | Keywords |
| --- | --- | --- |
| [boring.notch](https://github.com/TheBoredTeam/boring.notch) | Turns the MacBook notch into a dynamic island: music controls, and more. | `macos` `notch` `menu-bar` `swift` |
| [vorssaint-utils](https://github.com/vorssaint/vorssaint-utils) | Free and open source macOS menu bar toolkit. | `macos` `menu-bar` `toolkit` `swift` |
| [Ice](https://github.com/jordanbaird/Ice) | Powerful menu bar manager: hide, show, and arrange menu bar items. | `macos` `menu-bar` `manager` `swift` |
| [stats](https://github.com/exelban/stats) | macOS system monitor in the menu bar: CPU, GPU, memory, network, sensors. | `macos` `menu-bar` `monitoring` `swift` |

## Writing

| Repo | What it is | Keywords |
| --- | --- | --- |
| [no-ai-slop](https://github.com/petergyang/no-ai-slop) | Removes 20+ patterns of AI slop from any piece of writing. | `writing` `ai-slop` `editing` `python` |

## UI/UX

| Repo | What it is | Keywords |
| --- | --- | --- |
| [lenis](https://github.com/darkroomengineering/lenis) | Lightweight, robust smooth scroll. WebGL sync, parallax, buttery feel in a few lines. | `smooth-scroll` `parallax` `webgl` `vanilla-js` |
| [GSAP](https://github.com/greensock/GSAP) | The animation platform. ScrollTrigger alone is worth it. Every premium plugin now free, no license. | `animation` `scroll-trigger` `timeline` `text-effects` |
| [vanta](https://github.com/tengbao/vanta) | Animated 3D website backgrounds, three.js wrapped WebGL in about five lines of code. | `3d` `backgrounds` `three-js` `webgl` |
| [react-bits](https://github.com/DavidHDev/react-bits) | 130+ animated React components. Text effects, backgrounds, interactions. Great to port to vanilla too. | `react` `components` `text-effects` `animation` |
| [headroom.js](https://github.com/WickyNilliams/headroom.js) | Hide the header on scroll down, reveal on scroll up. Tiny, dependency free, does one thing well. | `header` `scroll` `navbar` `vanilla-js` |
| [originkit](https://github.com/vellum-ai/originkit) | Free library of 50 animated components, browsable and importable via MCP. | `components` `animation` `mcp` `typescript` |
| [img2threejs](https://github.com/img2threejs/img2threejs) | Rebuilds the object in a reference image as a code-only, procedural, animation-ready Three.js model. Token-efficient image-to-3D. | `3d` `three-js` `image-to-3d` `procedural` `python` |
| [awesome-design-md](https://github.com/voltagent/awesome-design-md) | DESIGN.md files distilled from popular brand design systems. Drop one into your project and coding agents generate a matching UI. | `design-systems` `ai-context` `agents` `curated` |
| [design.md](https://github.com/google-labs-code/design.md) | Google Labs' format spec for describing a visual identity to coding agents: a persistent, structured understanding of a design system. Install: [skills.sh](https://skills.sh/google-labs-code/design.md). | `design-systems` `ai-context` `spec` `google-labs` |
| [react-three-fiber](https://github.com/pmndrs/react-three-fiber) | A React renderer for Three.js. The standard way to do declarative 3D in React. | `3d` `three-js` `react` `webgl` |
| [shadergradient](https://github.com/ruucm/shadergradient) | Beautiful moving gradients for Framer, Figma, and React. | `gradients` `shaders` `react` `figma` `animation` |
| [liquid-glass-js](https://github.com/dashersw/liquid-glass-js) | Apple-inspired liquid glass UI effects library. | `glassmorphism` `effects` `ui` `vanilla-js` |
| [liquid-logo](https://github.com/collidingScopes/liquid-logo) | Free open source tool for animated logos with a liquid metal aesthetic, rendered real-time in the browser. | `logo` `animation` `liquid-metal` `browser` |
| [21st.dev](https://21st.dev/) | 12,000+ hand-crafted React and Tailwind components, templates, and shadcn themes. Preview live, install with one command, works for you and your AI agent. | `components` `react` `tailwind` `shadcn` `marketplace` |

## Design tools

| Resource | What it is | Keywords |
| --- | --- | --- |
| [Ditther](https://ditther.com/) | Free browser image effects editor, 75+ effects: dither, halftone, ASCII art, pixel art, voxel graphics. No install. | `design-tools` `image-effects` `dither` `ascii-art` `browser` |
| [Pryzm](https://pryzm.design/) | Visual studio for designers: original backgrounds and textures for sites and templates, generated in the browser in seconds. | `design-tools` `backgrounds` `textures` `browser` |

## Adding entries

One line per repo: link, what it does in plain words, and a handful of
lowercase keywords covering the problem it solves and the stack it runs on.
If a tool stops earning its place, it gets removed, not archived.
