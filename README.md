# Professional Typst Document & Engineering Report Template

A modern, highly modular technical and executive document template for [Typst](https://typst.app/). Designed for engineering whitepapers, research reports, technical specifications, and corporate documentation, it features an executive cover page, responsive Light and Dark theming, signature callout boxes, dashboard-style KPI metric cards, themed zebra tables, terminal consoles, and embedded fonts.

---

## Table of Contents

- [Visual Demos & PDF Downloads](#visual-demos--pdf-downloads)
- [Overview & Visual Identity](#overview--visual-identity)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Automation & Makefile](#automation--makefile)
- [Component Reference Guide](#component-reference-guide)
  - [1. Master Template & Executive Cover Page](#1-master-template--executive-cover-page)
  - [2. Callouts & Admonition Blocks](#2-callouts--admonition-blocks)
  - [3. Dashboard Widgets, Metric Cards & Grids](#3-dashboard-widgets-metric-cards--grids)
  - [4. Container Blocks: Left-Bar, Cards & Key-Value Grids](#4-container-blocks-left-bar-cards--key-value-grids)
  - [5. Code Blocks, Terminal Consoles & Inlines (SF Mono)](#5-code-blocks-terminal-consoles--inlines-sf-mono)
  - [6. Themed Data Tables (Zebra Alternating Fills)](#6-themed-data-tables-zebra-alternating-fills)
  - [7. Status Badges, Tech Tags & Protocol Chips](#7-status-badges-tech-tags--protocol-chips)
  - [8. Process Timelines & Step Flows](#8-process-timelines--step-flows)
  - [9. Table of Contents & Outlines](#9-table-of-contents--outlines)
- [Theming & Color Palettes](#theming--color-palettes)
- [Embedded Fonts](#embedded-fonts)

---

## Visual Demos & PDF Downloads

You can compile and view the rendered documents in both **Light** and **Dark** themes:

- 📄 **[Download Light Theme PDF (`output.pdf`)](output.pdf)**
- 📄 **[Download Dark Theme PDF (`output-dark.pdf`)](output-dark.pdf)**

Below is a visual showcase of the compiled document pages in both **Light** and **Dark** themes:

### 1. Executive Cover Page & Outlines

| Light Theme | Dark Theme |
|:---:|:---:|
| **Page 1: Title, Abstract & Executive Metadata Card** | **Page 1: Title, Abstract & Executive Metadata Card** |
| ![Light Cover Page](assets/preview/demo-light-page-01.png) | ![Dark Cover Page](assets/preview/demo-dark-page-01.png) |
| **Page 2: Table of Contents & List of Figures** | **Page 2: Table of Contents & List of Figures** |
| ![Light TOC & Figures](assets/preview/demo-light-page-02.png) | ![Dark TOC & Figures](assets/preview/demo-dark-page-02.png) |
| **Page 3: List of Tables** | **Page 3: List of Tables** |
| ![Light Tables Outline](assets/preview/demo-light-page-03.png) | ![Dark Tables Outline](assets/preview/demo-dark-page-03.png) |

### 2. Executive Overview & Paradigm Shift

| Light Theme | Dark Theme |
|:---:|:---:|
| **Page 4: Executive Overview & Architectural Comparison Table** | **Page 4: Executive Overview & Architectural Comparison Table** |
| ![Light Executive Overview](assets/preview/demo-light-page-04.png) | ![Dark Executive Overview](assets/preview/demo-dark-page-04.png) |
| **Page 5: Paradigm Shift, Highlight Boxes & Concept Callout** | **Page 5: Paradigm Shift, Highlight Boxes & Concept Callout** |
| ![Light Paradigm Shift](assets/preview/demo-light-page-05.png) | ![Dark Paradigm Shift](assets/preview/demo-dark-page-05.png) |

### 3. Architecture, Invariants & Topologies

| Light Theme | Dark Theme |
|:---:|:---:|
| **Page 6: End-to-End System Architecture Diagram** | **Page 6: End-to-End System Architecture Diagram** |
| ![Light System Architecture](assets/preview/demo-light-page-06.png) | ![Dark System Architecture](assets/preview/demo-dark-page-06.png) |
| **Page 7: Step-Flow Timeline, Left-Bar Box, Card Box & Key-Value Grid** | **Page 7: Step-Flow Timeline, Left-Bar Box, Card Box & Key-Value Grid** |
| ![Light Containers & Topology](assets/preview/demo-light-page-07.png) | ![Dark Containers & Topology](assets/preview/demo-dark-page-07.png) |

### 4. Engineering Challenges & Problem Resolutions

| Light Theme | Dark Theme |
|:---:|:---:|
| **Page 8: Clock Drift & Network Partitioning Challenge Boxes** | **Page 8: Clock Drift & Network Partitioning Challenge Boxes** |
| ![Light Engineering Challenges 1 & 2](assets/preview/demo-light-page-08.png) | ![Dark Engineering Challenges 1 & 2](assets/preview/demo-dark-page-08.png) |
| **Page 9: Configuration Console & Memory Backpressure Challenge** | **Page 9: Configuration Console & Memory Backpressure Challenge** |
| ![Light Configuration & Challenge 3](assets/preview/demo-light-page-09.png) | ![Dark Configuration & Challenge 3](assets/preview/demo-dark-page-09.png) |

### 5. Observability, Telemetry & Real-Time Monitoring

| Light Theme | Dark Theme |
|:---:|:---:|
| **Page 10: Real-Time Operations Console & 3x Metric KPI Cards** | **Page 10: Real-Time Operations Console & 3x Metric KPI Cards** |
| ![Light Operations Console & Metrics](assets/preview/demo-light-page-10.png) | ![Dark Operations Console & Metrics](assets/preview/demo-dark-page-10.png) |
| **Page 11: Subsystem Status Badges, Protocol Tags & Tech Chips** | **Page 11: Subsystem Status Badges, Protocol Tags & Tech Chips** |
| ![Light Badges & Chips](assets/preview/demo-light-page-11.png) | ![Dark Badges & Chips](assets/preview/demo-dark-page-11.png) |

### 6. Empirical Benchmarks & Operational Alerts

| Light Theme | Dark Theme |
|:---:|:---:|
| **Page 12: Quantitative Benchmarks Table & Operational Alert Suite (Info, Tip, Warning, Danger)** | **Page 12: Quantitative Benchmarks Table & Operational Alert Suite (Info, Tip, Warning, Danger)** |
| ![Light Benchmarks & Alerts](assets/preview/demo-light-page-12.png) | ![Dark Benchmarks & Alerts](assets/preview/demo-dark-page-12.png) |

### 7. Code Implementation, Formal Proofs & Conclusion

| Light Theme | Dark Theme |
|:---:|:---:|
| **Page 13: Rust Codeblock with Line Numbers, Terminal Console & Inlines** | **Page 13: Rust Codeblock with Line Numbers, Terminal Console & Inlines** |
| ![Light Codeblock & Terminal](assets/preview/demo-light-page-13.png) | ![Dark Codeblock & Terminal](assets/preview/demo-dark-page-13.png) |
| **Page 14: Quorum Intersection Mathematical Proof & Conclusion** | **Page 14: Quorum Intersection Mathematical Proof & Conclusion** |
| ![Light Formal Proof & Conclusion](assets/preview/demo-light-page-14.png) | ![Dark Formal Proof & Conclusion](assets/preview/demo-dark-page-14.png) |

---

## Overview & Visual Identity

This template delivers a modern, executive design language:

- **Executive Color Identity:**
  - `primary-color` (`#1e3a8a` Deep Navy): Document titles, section headings, and primary brand accents.
  - `secondary-color` (`#0f766e` Teal / Cyan): Subsection titles, code left-accent borders, and process arrows.
  - `accent-red` (`#b91c1c` Crimson Alert): Critical alerts, security mitigations, and negative deltas.
  - `bg-callout` / `border-callout` (`#f0fdf4` / `#16a34a` Soft Mint & Green): Architectural takeaways.
  - `bg-note` / `border-note` (`#eff6ff` / `#2563eb` Soft Sky Blue): Plain-English conceptual callouts.
  - `bg-challenge` / `border-challenge` (`#fff7ed` / `#ea580c` Warm Orange): Engineering challenge & resolution cards.
- **Embedded Fonts in `assets/fonts/`:**
  - **SF Mono**: Bundled monospace font used for codeblocks, inline badges, and terminal sessions.
  - **Roboto**: Bundled sans-serif font for running page headers, badges, and metadata labels.
  - **Libertinus Serif / New Computer Modern**: Standard academic and engineering serif typography for document body.
- **Single Import:** All styles, helpers, widgets, and templates are accessible through a single import:
  ```typst
  #import "prelude.typ": *
  ```
- **Dual-Theme Engine:** Complete native support for both **Light** and **Dark** rendering with automated contrast adjustment.

---

## Quick Start

### Minimal Document Example

Create your document (e.g. `main.typ`):

```typst
#import "prelude.typ": *

#show: document-template.with(
  title: "Cloud Engine Specification",
  subtitle: "High-Throughput Stream Processing Architecture",
  organization: "ENGINEERING RESEARCH LABS",
  author: ("Alex Mercer", "Core Infrastructure Team"),
  date: auto,
  version: "Release 1.0.0",
  domain: "Distributed Infrastructure / Cloud Computing",
  abstract: [
    This specification outlines the architecture, consensus mechanics, and benchmark results of the cloud streaming engine.
  ],
  cover-page: true,
  toc: true,
  lof: true,
  lot: true,
)

= Executive Overview

Traditional data pipelines face severe latency bottlenecks under burst workloads.

#callout(title: "In Simple Words: Conceptual Analogy", label: "SYSTEM ANALOGY")[
  Instead of polling a database periodically like a guard walking down a hallway, the engine uses an event radar that detects and routes traffic dynamically.
]

#takeaway(title: "Architectural Principle", label: "DESIGN PRINCIPLE")[
  Logs are the single source of truth. State is simply the current fold of an ordered event log.
]

= Engineering Challenges & Solutions

#challenge-box(
  challenge: "Distributed Clock Drift & Skew",
  problem: [NTP clock drift of up to 45ms caused causal event ordering inversions across nodes.],
  solution: [Formulated hybrid logical clocks (HLC) combining physical UNIX timestamps with monotonic logical counters.]
)

= System Observability & Telemetry

#metric-grid(
  columns: (1fr, 1fr, 1fr),
  metric-card(title: "Throughput", value: "2.42M ops/s", change: "+64.2% Uplift", change-positive: true),
  metric-card(title: "P99 Latency", value: "1.42 ms", change: "-42.8% Reduction", change-positive: true),
  metric-card(title: "Availability", value: "99.999%", change: "Zero Downtime", change-positive: true),
)

== Terminal Deployment

#consoleblock[
  #text(fill: rgb("#38bdf8"))[\$] git clone https://github.com/acme/cloud-engine.git\
  #text(fill: rgb("#38bdf8"))[\$] cd cloud-engine && make build\
  #text(fill: rgb("#4ade80"))[==> Compiling light document to output.pdf...]\
  #text(fill: rgb("#4ade80"))[==> Done: output.pdf]
]
```

---

## Project Structure

```text
typst-document-template/
├── prelude.typ            # Single entrypoint importing and exporting everything
├── template.typ           # Master document-template function (geometry, headers, show rules)
├── main.typ               # Comprehensive demonstration document
├── Makefile               # Automates compilation, dark mode, watching, and previews
├── README.md              # Full documentation and visual preview showcase
├── .gitignore             # Ignores compiled PDFs and temporary cache
├── assets/
│   ├── fonts/             # Embedded Roboto (TTF) and SF Mono (OTF) font families
│   │   ├── Roboto-*.ttf   # 12 styles/weights
│   │   └── SFMono-*.otf   # 12 styles/weights
│   ├── images/            # Technical diagrams and console screenshots
│   └── preview/           # Exported high-resolution preview images
│       └── demo-*.png     # 14 light & 14 dark page PNG previews
└── components/
    ├── theme.typ          # Light & Dark color palettes and reactive state
    ├── callouts.typ       # Concept Callout, Takeaway, Challenge, Info, Warning, Danger, Tip
    ├── boxes.typ          # Left-bar box, Card box, Metric cards, Metric grid, Key-value grid
    ├── badges.typ         # Status badges, Tech tags, Protocol chips, Generic badges
    ├── codeblock.typ      # Codeblocks with line numbers, Terminal console, Inline code
    ├── tables.typ         # Styled tables with zebra alternating fills
    ├── cover.typ          # Executive cover page layout generator
    ├── toc.typ            # Table of Contents headers and entry styling
    └── macros.typ         # Process flow timeline (step-flow) & math shortcuts
```

---

## Automation & Makefile

The included `Makefile` automates compiling, dark theme generation, live reloading, and preview extraction:

```bash
# Compile both Light (output.pdf) and Dark (output-dark.pdf) documents
make

# Compile standard Light theme document
make build

# Compile Dark theme document
make dark

# Live preview / auto-recompile on file save (Light theme)
make watch

# Live preview / auto-recompile on file save (Dark theme)
make watch-dark

# Export PDFs and convert pages into PNG demo images in assets/preview/
make previews

# Clean generated PDFs and preview images
make clean

# Display help message
make help
```

---

## Component Reference Guide

### 1. Master Template & Executive Cover Page

The master layout is initialized using `#show: document-template.with(...)`:

```typst
#show: document-template.with(
  title: "Document Title",
  subtitle: "Document Subtitle",
  organization: "ORGANIZATION OR RESEARCH LAB",
  author: ("Author 1", "Author 2"),
  date: auto,
  version: "Release 1.0.0",
  domain: "System Domain",
  abstract: [Abstract summary text goes here...],
  footer-note: [Custom footer note],
  confidential: "Confidential & Proprietary Notice",
  theme: sys.inputs.at("theme", default: "light"),
  paper: "a4",                          // "a4" or "us-letter"
  margin: (top: 2.6cm, bottom: 2.6cm, left: 2.5cm, right: 2.5cm),
  font: ("Libertinus Serif", "New Computer Modern"),
  sans-font: ("Roboto", "Liberation Sans"),
  mono-font: ("SF Mono", "IBM Plex Mono"),
  cover-page: true,                     // Renders executive cover card
  toc: true,                            // Generates Table of Contents
  toc-title: "Table of Contents",
  toc-depth: 3,
  toc-pagebreak: true,                  // Pagebreak after outlines
  lof: true,                            // Generates List of Figures
  lot: true,                            // Generates List of Tables
)
```

To render the cover page standalone without the wrapper, call `#render-cover-page(...)` directly.

### 2. Callouts & Admonition Blocks

All callout components automatically inherit the active theme palette:

| Component | Default Accent | Purpose |
|---|---|---|
| `#callout(title: ..., label: ...)[body]` | Blue (`#2563eb`) | Plain-English explanation / Conceptual analogy |
| `#takeaway(title: ..., label: ...)[body]` | Green (`#16a34a`) | Architectural principle / Key takeaway |
| `#challenge-box(challenge: ..., problem: ..., solution: ...)` | Orange (`#ea580c`) | Operational problem & engineering resolution |
| `#info(title: ..., label: ...)[body]` | Sky (`#0284c7`) | Informational notice |
| `#warning(title: ..., label: ...)[body]` | Amber (`#d97706`) | Operational precaution or caveat |
| `#danger(title: ..., label: ...)[body]` | Crimson (`#dc2626`) | High-severity invariant or security alert |
| `#tip(title: ..., label: ...)[body]` | Mint (`#16a34a`) | Pro-tip or performance recommendation |
| `#highlight-box(variant: "green")[body]` | Multi-color | Standout centered contrast box (blue, green, red, amber, neutral) |

#### Example: Challenge & Resolution Box
```typst
#challenge-box(
  challenge: "Distributed Clock Drift",
  problem: [NTP clock drift of 45ms caused causal inversions across nodes.],
  solution: [Implemented hybrid logical clocks combining UNIX timestamps with monotonic logical counters.]
)
```

### 3. Dashboard Widgets, Metric Cards & Grids

Display high-level KPIs, performance uplifts, and latency stats:

```typst
#metric-grid(
  columns: (1fr, 1fr, 1fr),
  metric-card(
    title: "Sustained Throughput",
    value: "2.42M ops/s",
    change: "+64.2% Uplift",
    change-positive: true,
    note: "vs. Standard Baseline"
  ),
  metric-card(
    title: "P99 Latency",
    value: "1.42 ms",
    change: "-42.8% Reduction",
    change-positive: true,
    note: "Sub-2ms Operational SLA"
  ),
  metric-card(
    title: "Cluster Uptime",
    value: "99.999%",
    change: "Zero Downtime",
    change-positive: true,
    note: "Tested over 180 Days"
  ),
)
```

### 4. Container Blocks: Left-Bar, Cards & Key-Value Grids

- **Left-Bar Invariant Box:**
  ```typst
  #left-bar-box(bar-color: secondary-color)[
    *Linearizable Consensus Invariant (Axiom 1.1):* Committed log entries are guaranteed to be present across all subsequent leaders.
  ]
  ```

- **Card Box with Header & Footer:**
  ```typst
  #card-box(
    title: "Cluster Topology Specification",
    label: "INFRASTRUCTURE",
    footer: "Verified against Jepsen Fault Injection Suite",
  )[
    - Quorum Requirement: Strict majority ($floor(N / 2) + 1$).
    - Heartbeat Periodicity: Uniform 50ms pulse rate.
  ]
  ```

- **Key-Value Metadata Grid:**
  ```typst
  #key-value-grid(
    columns: (1fr, 1fr),
    [ *Cluster Config:* 5 Nodes (Multi-AZ), 3x Replication ],
    [ *SLA Target:* P99 Latency $< 2"ms"$, Throughput $> 2"M ops/s"$ ]
  )
  ```

### 5. Code Blocks, Terminal Consoles & Inlines (SF Mono)

- **Standard Code Block with Line Numbers & Tab:**
  ```typst
  #codeblock(lang: "rust", filename: "src/consensus/raft.rs", line-numbers: true)[
    pub async fn apply_entry(&self, entry: LogEntry) -> Result<u64, Error> {
        // Implementation
    }
  ]
  ```

- **Terminal Console Block:**
  ```typst
  #consoleblock[
    #text(fill: rgb("#38bdf8"))[\$] typst compile main.typ output.pdf\
    #text(fill: rgb("#4ade80"))[==> Done: output.pdf]
  ]
  ```

- **Inline Code Snippet:**
  ```typst
  Reference methods directly with #codeinline[ConsensusEngine::apply_log_entry()].
  ```

### 6. Themed Data Tables (Zebra Alternating Fills)

Tables automatically use alternating zebra fills (`table.header-bg`, `even-bg`, `odd-bg`) matching the active theme:

```typst
#styled-table(
  columns: (2.2fr, 1.8fr, 1.8fr, 2.2fr),
  headers: ([*Metric*], [*Baseline*], [*Nexus Engine*], [*Delta*]),
  caption: [Empirical Performance Benchmark on 5-Node Cluster.],
  [*Write Throughput*], [1.15M ops/sec], [*2.42M ops/sec*], [#text(fill: rgb("#16a34a"))[+110.4% Uplift]],
  [*P99 Latency*], [3.84 ms], [*1.42 ms*], [#text(fill: rgb("#16a34a"))[63.02% Reduction]],
)
```

### 7. Status Badges, Tech Tags & Protocol Chips

- **Operational Status Badges:**
  ```typst
  #status-badge("allow", label: "ONLINE")      // Green ONLINE badge
  #status-badge("alert_admin", label: "WARN")  // Amber WARN badge
  #status-badge("isolate_device", label: "ERR")// Crimson ERR badge
  #status-badge("normal")                      // Slate NORMAL badge
  ```

- **Technology & Protocol Chips:**
  ```typst
  #tech-tag("Raft Consensus", category: "PROTOCOL")
  #tech-tag("Zero-Copy RingBuffer", category: "MEMORY")
  #protocol-tag("gRPC / HTTP/2")
  #badge("Production Certified")
  ```

### 8. Process Timelines & Step Flows

Visualize multi-step workflows with styled sequence badges and arrows:

```typst
#step-flow(
  [1. Ingest\ (Zero-Copy)],
  [2. Partition\ (Consistent Hash)],
  [3. Consensus\ (Raft Quorum)],
  [4. Apply\ (State Machine)],
  [5. Persist\ (Immutable WAL)],
)
```

### 9. Table of Contents & Outlines

Configured inside `document-template`:
- `toc: true` generates the Table of Contents.
- `lof: true` appends the List of Figures.
- `lot: true` appends the List of Tables.
- `toc-pagebreak: true` inserts a clean pagebreak after outlines.

---

## Theming & Color Palettes

The template provides two calibrated palettes: **Light** (default) and **Dark**.

To compile in dark mode:
```bash
typst compile --font-path assets/fonts --input theme=dark main.typ output-dark.pdf
```
Or with `make`:
```bash
make dark
```

Palette colors can be accessed directly or overridden via `resolve-palette()`:

```typst
#import "prelude.typ": resolve-palette, current-theme

#context {
  let p = resolve-palette()
  text(fill: p.primary)[This uses the active primary color]
}
```

---

## Embedded Fonts

Both font families are embedded directly in `assets/fonts/` for reproducible, self-contained compilation on any system:

- **SF Mono**: 12 weights & styles (Regular, Medium, Semibold, Bold, Heavy, Light with matching Italic variants).
- **Roboto**: 12 weights & styles (Thin, Light, Regular, Medium, Bold, Black with matching Italic variants).

To ensure Typst resolves the embedded fonts, pass `--font-path assets/fonts` (handled automatically by the included `Makefile`).
