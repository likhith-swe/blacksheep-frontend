# Black Sheep Engine — Master UI/UX Generation Prompt

> **Framework Alignment**: Built strictly adhering to [`/anti-vibe-design`](file:///Users/likhith/.gemini/config/skills/anti-vibe-design/SKILL.md) and [`/ui-ux-pro-max`](file:///Users/likhith/.gemini/config/skills/ui-ux-pro-max/SKILL.md).  
> **Target Tooling**: Copy-paste directly into **v0.dev**, **Lovable.dev**, **Bolt.new**, **Cursor Composer**, or **Claude 3.7 Sonnet**.  
> **Design Archetype**: **Swiss Modernism 2.0 & High-Precision Quantitative Terminal** (Linear meets Palantir Foundry and Teenage Engineering).  
> **Backend Integration**: Pointing directly to the active REST & SSE API at `http://localhost:5001`.

---

## Visual Audit of Existing Prototype

![Current UI Prototype](/Users/likhith/.gemini/antigravity/brain/7a1e7d01-f744-4e86-b47c-073d2455d721/current_ui_audit.png)

> [!WARNING] Design Deficiencies in the Current Prototype
> 1. **Logo Geometry Failure**: The hero logo text is cropped on the right edge ("BLACK SHEE") due to unconstrained raster scaling.
> 2. **Clinical White Glare**: Pure `#FFFFFF` background with default single-pixel grey borders creates optical eye strain and lacks editorial depth.
> 3. **Vibe-Coding Markers**: Raw dashed upload boxes, uncalibrated typography sizes, and missing micro-metric telemetry cards.
> 4. **Truncated Workflow Visibility**: The 5-step progression is hidden in bottom drawer cards rather than functioning as a cohesive, persistent command center.

---

# THE MASTER PROMPT (COPY EVERYTHING BELOW)

```markdown
# MISSION
Build a world-class, production-grade frontend for "Black Sheep Engine" — an enterprise-grade Autonomous Multi-Agent Collective Intelligence & Predictive Market Simulation Platform.

The platform allows quantitative analysts, venture capital partners, and product strategists to upload unstructured thesis documents, extract multi-dimensional domain ontologies, construct real-time temporal knowledge graphs, simulate up to 1,000,000 autonomous AI agents interacting across parallel social networks (Twitter/X and Reddit), watch an autonomous ReACT intelligence agent synthesize strategic market prediction reports in real-time, and directly interrogate simulated agents in a 1-on-1 interview room.

---

## 1. DESIGN SYSTEM & AESTHETIC DIRECTIVES (SWISS MODERNISM 2.0)

### Visual Philosophy
- **Style Archetype**: Swiss Modernism 2.0 & High-Precision Quantitative Terminal (inspired by Linear.app, Palantir Foundry, and Teenage Engineering hardware).
- **Tone**: Disciplined, mathematical, data-dense, authoritative, and calm. Zero playful AI gimmicks.
- **Color Discipline (Strict 60-30-10 Rule)**:
  - **Dominant Base (60%)**: Deep Engineered Slate `#0A0D14` (Dark Mode) or Refined Cool Linen `#F8F9FA` (Light Mode).
  - **Structural Surfaces (30%)**: Matte Charcoal `#111827` with 1px hairline rules (`border-slate-800` / `border-black/[0.08]`).
  - **Single Conversion Accent (10%)**: Precision Electric Cobalt `#1D4ED8` (Primary Action) with Warning Amber `#D97706` for simulation anomalies.
  - **Status Tokens**: Positive/Running `#10B981`, Warning/Paused `#F59E0B`, Failed/Critical `#EF4444`.
- **Typography Pairing**:
  - **Primary & Headings**: `Plus Jakarta Sans` or `Instrument Sans` (Optical weights: 400, 600, 700). Letter-spacing: `-0.02em` on titles.
  - **Data, Metrics & Agent Thought Streams**: `JetBrains Mono` or `Commit Mono` (Weights: 400, 500). Base size: 12px–13px with 1.4 line-height.
- **Geometry & Elevation**:
  - Border Radii: Strictly calibrated 6px (`rounded-md`) to 8px (`rounded-lg`). Nested radii rule: Inner = Outer - Padding.
  - Shadows: Layered multi-bounce diffuse ambient elevation (`box-shadow: 0 1px 2px rgba(0,0,0,0.03), 0 4px 12px rgba(0,0,0,0.05)`). Never use harsh single-stop black shadows.
- **Layout Rhythm**: Strict 8px base grid. Compact data padding (8px–12px) for high density.

---

## 2. NEGATIVE DESIGN CONSTRAINTS (DO NOT USE)
Do NOT include any of the 29 "vibe-coding" amateur design cliches:
1. NO harsh, oversaturated linear or rainbow gradients on text, cards, or borders.
2. NO default 24px Lucide icons on every heading or bullet; use custom inline SVGs or clean typographic badges.
3. NO pure #FFFFFF blinding backgrounds; use refined off-whites (#F8F9FA, #FAFAFA) or deep slate (#0A0D14).
4. NO rainbow coloring across cards (no card 1 blue, card 2 purple, card 3 pink). Maintain strict 60-30-10 discipline.
5. NO harsh single-layer black drop shadows; use multi-tier subtle ambient elevation or clean 1px hairline borders.
6. NO boilerplate "3 feature cards in a row" with icon-title-text; use real workflow stages and dense telemetry.
7. NO emojis (🚀, ✨, 🔥, 💡) in headers, buttons, or feature lists; use monochrome vector glyphs.
8. NO heavy liquid glass or frosted glassmorphism (backdrop-blur-md with white borders); use crisp, high-contrast surfaces.
9. NO em dashes ("—") in copy; write short, punchy, active human sentences.
10. NO default Inter or Geist font exhaustion; use Plus Jakarta Sans paired with JetBrains Mono.
11. NO colored left border stripes (border-l-4) on cards or callouts; use subtle hairline perimeter borders.
12. NO fake testimonials with stock avatars; show authentic telemetry, simulation statistics, and agent actions.
13. NO arbitrary bento grids without data rationale; use structured multi-column split views.
14. NO fake macOS terminal windows with red/yellow/green dots on non-developer CLI products.
15. NO "It's not X, it's Y" copy clichés; state capabilities directly with precision.
16. NO generic green checkmark circles for bullet lists; use descriptive micro-headings.
17. NO formulaic 3-tier pricing cards; focus entirely on the enterprise simulation workflow.
18. NO abstract 3D floating shapes; show real interactive knowledge graphs, D3 visualizations, and agent feeds.
19. NO oversized "rounded-3xl" pill radius on everything; use precise geometric corner radii (6px to 8px).
20. NO purple and black dark mode cliché (#09090b with violet glow); use rich slate navy (#0A0D14) with cobalt (#1D4ED8).
21. NO missing skeleton loaders; reserve layout space and use shimmer skeleton placeholders during fetches.
22. NO giant fuzzy radial background glow orbs behind headlines.
23. NO repeating CSS radial dot grids in hero sections.
24. NO sparkle icons (✨) or magic metaphors on buttons; use active verbs ("Execute Simulation", "Synthesize Report").
25. NO bouncing or animated looping arrows pointing at CTA buttons.
26. NO missing Terms of Service or Privacy links; provide complete enterprise footer scaffolding.
27. NO hyperactive hover animations; use subtle 150ms border/tint shifts without layout scaling.
28. NO eye-searing neon accents (#00FF66, #00FFFF); use calibrated, WCAG AAA compliant tones.

---

## 3. CORE ARCHITECTURE: THE 5 SIMULATION PIPELINE STAGES

The application must implement a persistent stage stepper navigation bar with 5 synchronized views:

### STAGE 1: REALITY SEED INGESTION & KNOWLEDGE GRAPH BUILDER
- **Input Matrix**:
  - Drag-and-drop document upload area supporting PDF, Markdown, and TXT files.
  - File upload card showing file name, byte size, parsing status, and extracted token volume.
  - Simulation Prompt Textarea: Monospace text area with clear placeholder: "Describe the market hypothesis, product launch, or policy change to simulate."
  - Advanced Configuration Accordion: Chunk size slider (200–1000 tokens), chunk overlap slider (20–100 tokens), and target agent scale selector (100 to 1,000,000 agents).
  - Primary Action Button: "Initialize Knowledge Extraction" with real-time progress bar.
- **Interactive Knowledge Graph Panel (D3.js Force-Directed)**:
  - 10 Entity Archetype Nodes: StartupFounder, QuickCommerceExecutive, ResidentInfluencer, LocalMerchant, TechProfessional, VentureCapitalist, MediaOutlet, Person, Organization, RWA.
  - Physics Controls: Charge strength, link distance, collision radius, and center gravity sliders.
  - Node Inspector Slide-out Panel: Clicking any node reveals its properties, degree centrality, connected relationships, and source citation from the uploaded document.
  - Visual Legend: Muted semantic colors for entity types with quick-filter checkboxes to isolate specific sub-graphs.

### STAGE 2: SIMULATION ENVIRONMENT SETUP & PERSONA GENERATION
- **Persona Generation Matrix**:
  - Real-time generation stream showing agent profiles as they are synthesized.
  - Distribution Visualizers:
    - MBTI Personality Distribution (16-type bar breakdown).
    - Stance Polarity Gauge: Bimodal curve showing Skeptics (-1.0 to -0.3), Neutrals (-0.2 to +0.2), and Advocates (+0.3 to +1.0).
    - Socio-Economic & Demographics: Role badges, community seniority, and consumption habits.
- **Simulation Timeline & Channel Scheduler**:
  - Duration Selector: 24h, 72h, or 168h simulated time.
  - Round Granularity: 30 min, 60 min, or 120 min per round.
  - Diurnal Activity Curve: Interactive timeline showing peak engagement hours (19:00–23:00 UTC) vs quiet hours (01:00–06:00 UTC).
  - Platform Toggles: Enable Twitter/X micro-blogging, Reddit threaded forums, or both.
  - Primary Action Button: "Deploy Environment & Launch Agents".

### STAGE 3: DUAL-CHANNEL REAL-TIME SOCIAL SIMULATION
- **Real-Time Telemetry Command Bar**:
  - Round Counter: "Round 24 of 168 (14.2% elapsed)".
  - Simulated Clock: "Day 2, 14:00 UTC (Peak Hour)".
  - Metrics Grid: Total Actions Count, Active Agents, Mean Community Sentiment Score (-1.0 to +1.0).
  - Playback Controls: Pause, Resume, Step Forward (1 round), and Stop Simulation buttons.
- **Dual-Channel Live Split View**:
  - **Left Column: Twitter / X Feed**:
    - Live-updating micro-blog stream.
    - Post card: Author avatar, Name, Role badge, Timestamp, Post content, Hashtags, Retweet count, Like count.
    - Quote-post cards with visual reference to original post.
  - **Right Column: Reddit Community Threads**:
    - Threaded discussion format with nested child comments (1-3 levels of indent).
    - Upvote/Downvote telemetry, author credibility badges, and moderation flags.
- **Live Sentiment Sparkline**:
  - Compact, real-time line chart tracking stance divergence over simulated rounds.

### STAGE 4: REACT STRATEGIC INTELLIGENCE & REPORT SYNTHESIS
- **Autonomous ReACT Reasoning Stream**:
  - Monospace terminal log with collapsible thought steps.
  - Step Card: "Thought ➔ Tool Call ➔ Observation ➔ Synthesis".
  - Tool Invocation Badges: `query_zep_graph`, `fetch_agent_actions`, `run_sentiment_regression`, `conduct_expert_interview`.
- **Executive Prediction Report Canvas**:
  - Structured Markdown rendering with clean typography.
  - Executive Summary with probability scores.
  - Quantitative Adoption Curve & User Backlash Risk Analysis.
  - Strategic Recommendations for Founders & Investors.
  - Action Bar: "Export Markdown", "Export PDF", "Regenerate Analysis".

### STAGE 5: 1-ON-1 INTERACTIVE AGENT INTERROGATION ROOM
- **Agent Roster Sidebar**:
  - Filter agents by stance (Skeptic / Neutral / Evangelist), entity type, or activity volume.
  - Agent Card: Avatar, Name, Persona Bio, MBTI, Stance Score, and recent actions count.
- **Interactive Interview Chat Panel**:
  - Direct 1-on-1 chat interface with the selected agent.
  - Agent answers strictly in character, drawing upon all memories, posts, and thread debates from Stage 3.
  - Memory Context Drawer: Slide-out drawer displaying the exact historical actions and graph relationships that informed the agent's response.
  - Quick Questions Prompts: "Why did you oppose the group buying model?", "What price would change your mind?", "Who influenced your decision?".

---

## 4. TECHNICAL STACK & API INTEGRATION CONTRACT

### Tech Stack Recommendation
- **Framework**: React 19 (or Vue 3) + Vite + Tailwind CSS v4.
- **Data Visualization**: D3.js (force graph) + Recharts / Chart.js (sentiment & adoption curves).
- **Icons**: Custom inline SVGs (no Lucide icon overload).
- **State Management**: TanStack Query / Pinia + Zustand for simulation state.

### REST & SSE API Specification (`http://localhost:5001`)
- `POST /api/graph/upload`: Multipart upload with `files`, `simulation_requirement`, `project_name`.
- `GET /api/graph/<graph_id>`: Fetch nodes and edges for D3 graph rendering.
- `POST /api/simulation/create`: Initialize simulation state with `project_id`, `graph_id`.
- `POST /api/simulation/prepare`: Trigger background agent persona generation.
- `GET /api/simulation/<sim_id>/profiles`: Fetch generated agent profiles list.
- `POST /api/simulation/start`: Start simulation loop with `simulation_id`, `max_rounds`.
- `GET /api/simulation/<sim_id>/run-status`: Poll current round, progress percent, total actions.
- `GET /api/simulation/<sim_id>/actions`: Fetch Twitter & Reddit action logs stream.
- `POST /api/simulation/stop`: Gracefully terminate simulation runner.
- `POST /api/report/start`: Trigger autonomous ReACT report synthesis agent.
- `GET /api/report/<report_id>/stream`: SSE endpoint for real-time ReACT terminal logs.
- `GET /api/report/<report_id>`: Fetch finalized Markdown executive report.
- `POST /api/simulation/interview`: Send message to specific agent with `{ simulation_id, interviews: [{ agent_id, prompt }] }`.

---

## 5. ACCESSIBILITY & PERFORMANCE STANDARDS
- WCAG AA contrast ratio ($\ge 4.5:1$) for all body copy and badges.
- Content-aware skeleton loaders for all asynchronous fetch states (reserve height to keep CLS $< 0.1$).
- Full keyboard navigation support (Tab navigation, Esc to close drawers, Space/Enter to trigger actions).
- Responsive breakpoint preservation: 375px (mobile), 768px (tablet), 1280px (desktop), 1920px (ultrawide data terminal).
```
