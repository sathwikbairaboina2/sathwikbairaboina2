# Sathwik Bairaboina

> **Senior Full Stack Engineer · AI Solution Architect.** The model proposes. The deterministic core disposes.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/sathwik-bairaboina-630433182/) [![Email](https://img.shields.io/badge/bairaboinasathwik@gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:bairaboinasathwik@gmail.com) [![Portfolio](https://img.shields.io/badge/AI_Avatara-live-22c55e)](https://www.aiavatara.chat/about) [![Demo](https://img.shields.io/badge/demo-YouTube-FF0000?logo=youtube&logoColor=white)](https://youtu.be/5753AhC2ysw)

| years | public repos | workshop repos | workshop lines | workshop commits | workshop tests |
|:-:|:-:|:-:|:-:|:-:|:-:|
| **8+** | **19** | **25** | **270k** | **2,357** | **2,875** |

## `whoami`

Full stack engineer, eight years of it. Currently co-founding **Lego Verse Module**, building AI-driven SaaS on AWS.

The line I care about most in a system design: **where the model is allowed to make a decision, and where it is not.** Almost everything I ship has the same skeleton. A deterministic core owns state, money and limits. A probabilistic layer around it *proposes* rather than executes. Then a test asserts that every declared limit is actually enforced, which is where most agentic systems quietly fail.

| principle | in practice |
|---|---|
| ⛓️ **The LLM never executes** | Models classify, draft and propose. A rules engine approves, sizes and commits. Tests enforce the boundary. |
| 🏠 **Local-first by default** | Ollama, whisper.cpp, ComfyUI, Qdrant. If it can run on the host, it does. Cloud is a target, not a dependency. |
| 🔪 **Vertical slices** | Ship a complete flow, not a layer. Every slice is demoable the day it lands. |
| 📏 **Measured, not claimed** | Every headline number comes from a benchmark committed next to the code. |

## `stack`

| area | tools |
|---|---|
| **Languages** | `TypeScript` `Python` `Go` `Node.js` |
| **AI · agents** | `LangGraph` `LangChain` `Ollama` `Anthropic` `Hugging Face` `TensorFlow` `MCP` |
| **Frontend** | `React` `Next.js` `Angular` `Redux` `Storybook` `React Native` `WebGPU` |
| **Backend** | `NestJS` `FastAPI` `GraphQL` `Express` |
| **Cloud · data** | `AWS` `CDK` `Step Functions` `Docker` `Kubernetes` `DynamoDB` `PostgreSQL` `MongoDB` `Redis` `Elasticsearch` |

## `shipped in public`

Nineteen open-source repos. Every number below comes from a benchmark committed in that repo.

<sub>**GUARDRAILS FOR LLMS**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| 🚦 | [**tollgate**](https://github.com/sathwikbairaboina2/tollgate) | LLM gateway in Go. <sub>Go · OpenTelemetry · Prometheus</sub> | `+0.129 ms p50`<br/>`91.5% cost cut` |
| 🛡️ | [**toolwarden**](https://github.com/sathwikbairaboina2/toolwarden) | MCP security auditor. <sub>TypeScript · MCP SDK · GitHub Action</sub> | `5 MCP servers scanned`<br/>`6 findings, all reviewed` |
| 🧪 | [**evalgate**](https://github.com/sathwikbairaboina2/evalgate) | Agent regression tests in CI. <sub>TypeScript · GitHub Action · LLM judge</sub> | `p = 0.031 caught`<br/>`κ 1.0 judge` |
| 🏗️ | [**infra-agent**](https://github.com/sathwikbairaboina2/infra-agent) | Guardrailed Terraform agent. <sub>Python · LangGraph · Terraform · OPA</sub> | `0 / 24 violations applied` |
| 🔎 | [**deep-research**](https://github.com/sathwikbairaboina2/deep-research) | Research agent with a citation verifier. <sub>Python · LangGraph · Ollama</sub> | `0 bad citations shipped`<br/>`812 / 812 fakes rejected` |
| 🚨 | [**rca-bot**](https://github.com/sathwikbairaboina2/rca-bot) | Alarm to root-cause bot. <sub>TypeScript · Step Functions · Logs Insights</sub> | `90.9% top-1 root cause`<br/>`30 / 30 fabrications blocked` |

<sub>**AGENT RUNTIMES AND TOOLING**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| ⚡ | [**serverless-agent**](https://github.com/sathwikbairaboina2/serverless-agent) | LangGraph on Lambda, as a CDK construct. <sub>TypeScript · AWS CDK · LangGraph.js</sub> | `718 / 718 conformance`<br/>`0 IAM wildcards` |
| 🧾 | [**durable-multi-agent**](https://github.com/sathwikbairaboina2/durable-multi-agent) | Human-gated procurement agents. <sub>TypeScript · Step Functions · LangGraph</sub> | `0 duplicate POs`<br/>`$0.00 budget drift` |
| ⏪ | [**flight-recorder**](https://github.com/sathwikbairaboina2/flight-recorder) | Time-travel debugger for LangGraph. <sub>Python · FastAPI · React</sub> | `10k checkpoints in 372 ms` |
| ✍️ | [**co-author**](https://github.com/sathwikbairaboina2/co-author) | AI as a CRDT peer. <sub>TypeScript · Yjs · ProseMirror</sub> | `32 peers in 468 ms`<br/>`1.1 ms write gate` |

<sub>**INFRASTRUCTURE FROM SCRATCH, IN GO**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| 📨 | [**kafka-go**](https://github.com/sathwikbairaboina2/kafka-go) | Kafka broker from scratch. <sub>Go · stdlib only</sub> | `2.2 GB/s produce`<br/>`0 acked lost / 40 kill -9` |
| ♻️ | [**workflow-engine**](https://github.com/sathwikbairaboina2/workflow-engine) | Durable workflow engine. <sub>Go · SQLite</sub> | `0 lost / 200 kill -9`<br/>`703 transitions/s` |

<sub>**EVENT-DRIVEN AWS**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| 🧹 | [**etl-quarantine**](https://github.com/sathwikbairaboina2/etl-quarantine) | ETL with row-level quarantine. <sub>TypeScript · Step Functions · Parquet</sub> | `1M rows, 0 lost, 0 dupes` |
| 🛰️ | [**iot-telemetry**](https://github.com/sathwikbairaboina2/iot-telemetry) | Fleet telemetry and geofence alerts. <sub>TypeScript · MQTT · AWS IoT</sub> | `p99 7.2 ms`<br/>`0 duplicate alerts` |
| 💹 | [**pricing-engine**](https://github.com/sathwikbairaboina2/pricing-engine) | Stream-driven pricing engine. <sub>TypeScript · DynamoDB Streams · AppSync</sub> | `p50 172.5 ms to subscriber`<br/>`0 lost` |

<sub>**BROWSER AND FRONTEND**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| 🪄 | [**inpaint-web**](https://github.com/sathwikbairaboina2/inpaint-web) | In-browser object removal. <sub>TypeScript · onnxruntime-web · WebGPU</sub> | `38.9× WebGPU vs WASM` |
| 📈 | [**webgpu-chart**](https://github.com/sathwikbairaboina2/webgpu-chart) | Streaming chart on WebGPU. <sub>TypeScript · WebGPU · WGSL</sub> | `p95 6.4 ms vs 46.7 ms uPlot` |
| 🖍️ | [**whiteboard**](https://github.com/sathwikbairaboina2/whiteboard) | Local-first whiteboard. <sub>TypeScript · Yjs · WebRTC</sub> | `3.2 ms p95 paint, 10k shapes` |
| 🎨 | [**design-system**](https://github.com/sathwikbairaboina2/design-system) | Design system and micro-frontends. <sub>React · Module Federation · Storybook</sub> | `88 screenshots`<br/>`0 serious a11y` |

## `the workshop`

Ten systems that run on my own hardware, plus the harness that boots them and the live platform. One thesis, applied ten different ways. Repos without a `public` tag are private; happy to walk anyone through them.

<sub>**AGENTS WITH A DETERMINISTIC CORE**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| 🏬 | [**marketplace**](https://github.com/sathwikbairaboina2/marketplace) | Multi-tenant commerce with a schema agent. A chat proposes schema changes; the engine adjudicates them. <sub>NestJS ×2 · Next.js · LangGraph.js · LocalStack · Playwright</sub> | `30.8k lines`<br/>`346 commits` |
| 📈 | [**RakshaQuant**](https://github.com/sathwikbairaboina2/RakshaQuant) | Agentic NSE paper trading. Agents read the market; a rules engine approves, sizes and places. <sub>Python 3.11 · LangGraph · Groq · LangSmith · uv</sub> | `19.9k lines`<br/>`113 commits` |
| 🎓 | [**PersonalAITutor**](https://github.com/sathwikbairaboina2/PersonalAITutor) | Mastery-tracking tutor. Per-concept mastery that decays and replays from the attempt log. <sub>NestJS ×2 · LangGraph.js · mathjs · DynamoDB + S3</sub> | `9.3k lines`<br/>`91 commits` |
| 🔍 | [**AeoGeo**](https://github.com/sathwikbairaboina2/AeoGeo) | AI-search visibility scanner. How citable a site is to LLM search engines, tracked over time. <sub>NestJS · Turborepo + pnpm · DynamoDB · LangGraph.js</sub> | `8.9k lines`<br/>`31 commits` |

<sub>**LOCAL-FIRST AI APPS**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| 🎭 | [**Avatara**](https://github.com/sathwikbairaboina2/avatara-backend) <sub>`public`</sub> | Character chat for ages 6 to 17. Every sentence passes a deterministic safety gate before it streams; the model runs locally. <sub>NestJS ×2 · Next.js · LangGraph · Ollama · Redis · DynamoDB</sub> | `53.2k lines`<br/>`337 commits` |
| 💥 | [**ComicGen**](https://github.com/sathwikbairaboina2/ComicGen) <sub>`public`</sub> | Local comic studio. A topic goes in; a finished, lettered comic page comes out. <sub>Python 3.12 · FastAPI · ComfyUI / FLUX · Ollama · Pydantic v2</sub> | `10.2k lines`<br/>`111 commits` |
| 👻 | [**Invisible**](https://github.com/sathwikbairaboina2/Invisible) <sub>`public`</sub> | Capture-excluded meeting overlay. Live transcription and advice the screen recorder never sees. <sub>Electron 43 · React 19 · whisper.cpp · Silero VAD · Qdrant</sub> | `~673 ms to first word`<br/>`148 commits` |
| 🗓️ | [**personalAssistant**](https://github.com/sathwikbairaboina2/personalAssistant) | Local-first life tracker with voice. Every action also works with the AI switched off. <sub>NestJS · Next.js · faster-whisper · kokoro TTS · LocalStack</sub> | `13.0k lines`<br/>`68 commits` |

<sub>**PIPELINES AND TOOLING**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| 📸 | [**IntaBot**](https://github.com/sathwikbairaboina2/IntaBot) | Agentic Instagram operations. Draft, schedule, approve and publish as a state machine. <sub>NestJS · Next.js · BullMQ · MinIO / S3 · Anthropic · Zod</sub> | `6.0k lines`<br/>`54 commits` |
| 📥 | [**instascraper**](https://github.com/sathwikbairaboina2/instascraper) | Serialized media fetcher. One worker thread makes rate limiting structural. <sub>Next.js · FastAPI · Instaloader · Docker</sub> | `12.8k lines`<br/>`127 commits` |
| 🛠️ | [**_devkit**](https://github.com/sathwikbairaboina2/_devkit) | Workshop boot harness. Cold boot, health check and tests for nine projects, one command each. <sub>PowerShell · Docker Compose · LocalStack</sub> | `9 projects`<br/>`2,875 tests` |

<sub>**LIVE**</sub>

| | repo | what it is | measured |
|:-:|---|---|---|
| 🧬 | [**AI Avatara**](https://www.aiavatara.chat/about) <sub>`live`</sub> | End-to-end AI web platform on open-source transformer and diffusion models. [Watch the demo](https://youtu.be/5753AhC2ysw). <sub>Transformers · Diffusion models · Full stack</sub> | `hosted`<br/>`public demo` |

## `the rest of the bench`

Thirteen more private repos: plugins, services and tools that feed the systems above.

| | repo | what it is | measured |
|:-:|---|---|---|
| 🗒️ | **instastudio** | Structured JSON into Instagram-ready handwritten-notes carousels, with an AI revise chat and optional ComfyUI polish. | `7.6k lines`<br/>`240 commits` |
| 🔬 | **research assistant** | Local-only deep research with a local Qwen model, returning a cited report with the process visible live. | `15.7k lines`<br/>`117 commits` |
| 🖥️ | **AI Avatara front end** | The Next.js web client for the live AI Avatara platform. | `7.5k lines`<br/>`195 commits` |
| 💼 | **jobs reel** | A weekly sheet of open roles becomes one 60-second vertical reel. | `11.2k lines`<br/>`82 commits` |
| 🎬 | **reel renderer** | JSON in, reel out. A FastAPI service rendering Remotion reels in four themes. | `3.4k lines`<br/>`56 commits` |
| 🎧 | **HearSync** | Upload a PDF and read it in a reflowed reader that reads to you, or follows along as you read aloud. | `7.9k lines`<br/>`46 commits` |
| ☁️ | **AI Avatara infra** | AWS CDK infrastructure for the AI Avatara platform. | `2.7k lines`<br/>`44 commits` |
| 🧩 | **instacreator** | Takes a reference Instagram post and produces an original one: analyse, concept, generate, bundle. | `10.4k lines`<br/>`43 commits` |
| 📚 | **ComicGen Pro** | Director-grade comic and episode generator. Writers room on local Ollama, hard credit governance. | `5.0k lines`<br/>`32 commits` |
| 🧭 | **reelscout** | A topic becomes a reviewed pack of source material: six source hunters plus an adversarial critic. | `5.3k lines`<br/>`16 commits` |
| 🗣️ | **lipsync desk** | Reference image plus an audio file in, a closeup video of a person speaking it out. | `6.2k lines`<br/>`15 commits` |
| 📱 | **webpage → mp4** | A list of links becomes a vertical reel that looks like someone browsing each page on a phone. | `4.6k lines`<br/>`2 commits` |
| 🧮 | **Vyuha** | A curated per-person profile for LLM apps. The model proposes edits; the library validates, scans and writes them. | `TypeScript library`<br/>`11 commits` |

## `work experience`

| | company | role | dates |
|:-:|---|---|---|
| 🟢 | **Lego Verse Module** | Senior Full Stack Engineer · Co-Founder | Aug 2023 – present |
| 🇩🇪 | **Epilot GmbH** | Full Stack Engineer | Aug 2022 – May 2023 |
| | **Aithinkers** | Senior Software Developer | May 2021 – Aug 2022 |
| | **Iolar Technologies** | Full Stack Engineer | Dec 2017 – May 2021 |
| | **CMAE Technologies** | Senior Full Stack Engineer | Jan 2017 – Dec 2017 |

**Lego Verse Module** · `50% faster deploys` `99.99% uptime`
- Architected an AI-driven B2B SaaS platform on AWS, with LangChain and Hugging Face models automating complex workflows.
- Docker microservices auto-scaling on ECS, GraphQL APIs, and CI/CD through CDK and CloudFormation with automated tests.
<sub>Next.js · React · Node.js · Lambda · DynamoDB · AWS CDK · LangChain · Hugging Face · GraphQL · Docker · ECS</sub>

**Epilot GmbH** · `95% of UI bugs caught pre-release` `30% faster load times`
- Built import and export for dynamic platform entities with JSON Schema transformations, a Shopify-like model for arbitrary tenant data.
- Created a Storybook-driven component library with automated tests, and cut React/Redux bundle size.
<sub>Node.js · React · TypeScript · Redux · Storybook · JSON Schema</sub>

**Aithinkers**
- Led the rebuild of the AeroPartsNow aerospace e-commerce front end.
- Built a real-time dynamic pricing engine on Lambda, DynamoDB and Elasticsearch, and AppSync GraphQL APIs. Automated CI/CD with SAM, and set the team's coding standards.
<sub>React · Node.js · Lambda · DynamoDB · Elasticsearch · AppSync · AWS SAM · CloudFormation</sub>

**Iolar Technologies**
- Architected an on-demand vehicle maintenance platform (MERN plus a React Native app) with real-time booking and tracking.
- Integrated Google Maps, Razorpay, Plivo and OneSignal. Recruited and mentored the engineering team.
<sub>React · React Native · Node.js · Express · MongoDB · EC2 · S3</sub>

**CMAE Technologies**
- Built the backend for an IoT car platform: vehicle data over MQTT and CAN-BUS from Raspberry Pi ECUs into MongoDB on AWS.
- Collision detection, overspeed alerts, trip analysis, and geofenced theft alerts with MongoDB geospatial queries.
<sub>Python · Node.js · MQTT · CAN-BUS · MongoDB · Raspberry Pi · AWS</sub>

## `next`

**Open to senior and staff roles in AI platform engineering**, especially where the hard part is the boundary between the model and the system of record.

[![Let's talk](https://img.shields.io/badge/Let's_talk-LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/sathwik-bairaboina-630433182/) [![Email](https://img.shields.io/badge/bairaboinasathwik@gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:bairaboinasathwik@gmail.com)
