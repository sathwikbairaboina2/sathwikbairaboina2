# Stack Tags — Six Treatments

GitHub strips inline `style` attributes from markdown HTML, so a real CSS border in a custom colour is not achievable. These are the six things that actually render. Same tag list every time.

---

## G1 — Current: inline code

<sub>What's on `main` now. GitHub's default chip — soft grey fill, no border, colour follows the viewer's theme.</sub>

`NestJS ×2` · `Next.js` · `LangGraph.js` · `LocalStack` · `Playwright`

`Electron 43` · `React 19` · `whisper.cpp` · `Silero VAD` · `Qdrant`

---

## G2 — `<kbd>` — a genuine border

<sub>The only option with a true 1px border on all four sides. GitHub draws it itself, which is why it cannot be recoloured — it follows the viewer's theme (grey in light, lighter grey in dark). Slight 3D key-cap shading.</sub>

<kbd>NestJS ×2</kbd> <kbd>Next.js</kbd> <kbd>LangGraph.js</kbd> <kbd>LocalStack</kbd> <kbd>Playwright</kbd>

<kbd>Electron 43</kbd> <kbd>React 19</kbd> <kbd>whisper.cpp</kbd> <kbd>Silero VAD</kbd> <kbd>Qdrant</kbd>

---

## G3 — Cyan edge bar

<sub>Empty shields label in cyan, dark chip body. Reads as a coloured left border on every tag. Closest achievable to the ask.</sub>

![](https://img.shields.io/badge/-NestJS%20×2-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-Next.js-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-LangGraph.js-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-LocalStack-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-Playwright-0d1117?style=flat-square&labelColor=0EA5E9)

![](https://img.shields.io/badge/-Electron%2043-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-React%2019-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-whisper.cpp-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-Silero%20VAD-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-Qdrant-0d1117?style=flat-square&labelColor=0EA5E9)

---

## G4 — Solid cyan tags

<sub>Full cyan fill, dark text. No border, but maximum colour. Loudest of the six — competes with the stat badges above each card.</sub>

![](https://img.shields.io/badge/NestJS%20×2-0EA5E9?style=flat-square&logoColor=0d1117)
![](https://img.shields.io/badge/Next.js-0EA5E9?style=flat-square)
![](https://img.shields.io/badge/LangGraph.js-0EA5E9?style=flat-square)
![](https://img.shields.io/badge/LocalStack-0EA5E9?style=flat-square)
![](https://img.shields.io/badge/Playwright-0EA5E9?style=flat-square)

![](https://img.shields.io/badge/Electron%2043-0EA5E9?style=flat-square)
![](https://img.shields.io/badge/React%2019-0EA5E9?style=flat-square)
![](https://img.shields.io/badge/whisper.cpp-0EA5E9?style=flat-square)
![](https://img.shields.io/badge/Silero%20VAD-0EA5E9?style=flat-square)
![](https://img.shields.io/badge/Qdrant-0EA5E9?style=flat-square)

---

## G5 — Dark tags, navy edge

<sub>Same construction as G3 but the edge is `#1e3a5f` navy instead of cyan. Quieter — keeps cyan reserved for the numbers that matter.</sub>

![](https://img.shields.io/badge/-NestJS%20×2-0d1117?style=flat-square&labelColor=1e3a5f)
![](https://img.shields.io/badge/-Next.js-0d1117?style=flat-square&labelColor=1e3a5f)
![](https://img.shields.io/badge/-LangGraph.js-0d1117?style=flat-square&labelColor=1e3a5f)
![](https://img.shields.io/badge/-LocalStack-0d1117?style=flat-square&labelColor=1e3a5f)
![](https://img.shields.io/badge/-Playwright-0d1117?style=flat-square&labelColor=1e3a5f)

![](https://img.shields.io/badge/-Electron%2043-0d1117?style=flat-square&labelColor=1e3a5f)
![](https://img.shields.io/badge/-React%2019-0d1117?style=flat-square&labelColor=1e3a5f)
![](https://img.shields.io/badge/-whisper.cpp-0d1117?style=flat-square&labelColor=1e3a5f)
![](https://img.shields.io/badge/-Silero%20VAD-0d1117?style=flat-square&labelColor=1e3a5f)
![](https://img.shields.io/badge/-Qdrant-0d1117?style=flat-square&labelColor=1e3a5f)

---

## G6 — `<kbd>` inside a cyan rule

<sub>Real borders from G2, with a thin cyan divider above the row to carry the accent colour. Compromise: genuine borders plus cyan on the page.</sub>

<img src="https://img.shields.io/badge/-0EA5E9?style=flat-square&labelColor=0EA5E9&color=0EA5E9" height="2" width="120" alt="" />

<kbd>NestJS ×2</kbd> <kbd>Next.js</kbd> <kbd>LangGraph.js</kbd> <kbd>LocalStack</kbd> <kbd>Playwright</kbd>

<img src="https://img.shields.io/badge/-0EA5E9?style=flat-square&labelColor=0EA5E9&color=0EA5E9" height="2" width="120" alt="" />

<kbd>Electron 43</kbd> <kbd>React 19</kbd> <kbd>whisper.cpp</kbd> <kbd>Silero VAD</kbd> <kbd>Qdrant</kbd>

---

## In context — G3 inside a real card

<table><tr><td width="50%" valign="top">

#### 🏬 &nbsp;marketplace
**Multi-tenant commerce + schema agent**

*A chat that safely rewrites your database schema.*

Two services decoupled by an SQS FIFO queue. A deterministic engine enforces a per-tenant dynamic schema registry; a LangGraph layer turns a conversation into a validated schema-change proposal.

![](https://img.shields.io/badge/37.9k_lines-0d1117?style=flat-square)
![](https://img.shields.io/badge/489_files-0d1117?style=flat-square)
![](https://img.shields.io/badge/293_commits-0EA5E9?style=flat-square&labelColor=0d1117)

![](https://img.shields.io/badge/-NestJS%20×2-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-Next.js-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-LangGraph.js-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-LocalStack-0d1117?style=flat-square&labelColor=0EA5E9)

</td><td width="50%" valign="top">

#### 👻 &nbsp;Invisible
**Capture-excluded meeting overlay**

*Transparent to you. Invisible to the screen recorder.*

Listens, transcribes, streams advice onto an overlay excluded from screen capture. **~673 ms to first word.** Audio never hits disk.

![](https://img.shields.io/badge/8.7k_lines-0d1117?style=flat-square)
![](https://img.shields.io/badge/68_files-0d1117?style=flat-square)
![](https://img.shields.io/badge/74_commits-0EA5E9?style=flat-square&labelColor=0d1117)

![](https://img.shields.io/badge/-Electron%2043-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-React%2019-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-whisper.cpp-0d1117?style=flat-square&labelColor=0EA5E9)
![](https://img.shields.io/badge/-Qdrant-0d1117?style=flat-square&labelColor=0EA5E9)

</td></tr></table>

---

## In context — G2 `<kbd>` inside a real card

<table><tr><td width="50%" valign="top">

#### 🏬 &nbsp;marketplace
**Multi-tenant commerce + schema agent**

*A chat that safely rewrites your database schema.*

Two services decoupled by an SQS FIFO queue. A deterministic engine enforces a per-tenant dynamic schema registry; a LangGraph layer turns a conversation into a validated schema-change proposal.

![](https://img.shields.io/badge/37.9k_lines-0d1117?style=flat-square)
![](https://img.shields.io/badge/489_files-0d1117?style=flat-square)
![](https://img.shields.io/badge/293_commits-0EA5E9?style=flat-square&labelColor=0d1117)

<kbd>NestJS ×2</kbd> <kbd>Next.js</kbd> <kbd>LangGraph.js</kbd> <kbd>LocalStack</kbd>

</td><td width="50%" valign="top">

#### 👻 &nbsp;Invisible
**Capture-excluded meeting overlay**

*Transparent to you. Invisible to the screen recorder.*

Listens, transcribes, streams advice onto an overlay excluded from screen capture. **~673 ms to first word.** Audio never hits disk.

![](https://img.shields.io/badge/8.7k_lines-0d1117?style=flat-square)
![](https://img.shields.io/badge/68_files-0d1117?style=flat-square)
![](https://img.shields.io/badge/74_commits-0EA5E9?style=flat-square&labelColor=0d1117)

<kbd>Electron 43</kbd> <kbd>React 19</kbd> <kbd>whisper.cpp</kbd> <kbd>Qdrant</kbd>

</td></tr></table>
