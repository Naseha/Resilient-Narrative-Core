# Resilient-Narrative-Core
This protocol exists because atmosphere is easy and drive is harder. The framework now prefers the harder thing. The gate is non-negotiable.
# RP Storyteller & Character Empathy Engine (v2)

An open-source state-machine framework and prompt-engineered skill suite for large language models (LLMs) designed to solve **Alignment Collapse**, **Context Amnesia**, and **Passive Driver Loops** in long-form, high-intensity interactive narratives[cite: 5, 8].

---

## 📌 The Problem
Standard conversational LLMs degrade significantly over long-turn interactions (50+ turns)[cite: 5, 8]:
1. **Context Amnesia & Drift:** Fine-grained physical states, object custody, and lore slip as context windows roll over[cite: 5, 8].
2. **Driver Collapse:** Models default to passive hand-offs ("What do you want to do next?") rather than asserting narrative agency[cite: 5, 8].
3. **The "Therapeutic Caretaker" Reflex:** Under high emotional tension and mild friction/resistance, models drop character persona and default to corporate, sanitized consent menus (*"Ask me anything... all options are allowed"*)[cite: 5, 7, 8].
4. **Cultural & Cliché Degradation:** Language degenerates into generic romance clichés or orientalist tropes[cite: 1, 2, 8].

---

## 🛠 Architectural Solutions

* **Decoupled Spine Architecture:** Isolates load-bearing state variables, living Character Cards, and Crucial Moments into dedicated external spine files (`artifacts/RP/[Name]-spine.md`)[cite: 5].
* **Agency Enforcement & Default Ending Posture:** Hard cadence gate ($\ge 1$ meaningful change every 2 beats) requiring every turn to terminate on an irreversible physical or situational fact[cite: 5].
* **Heat & Resistance Protocol:** Tracks lived empathy metrics as a live tripwire ($\ge 1.0$ drop triggers mandatory rollbacks and rewrites to prior character attributes)[cite: 5, 7].
* **Mathematical Empathy Evaluation:** Grounded in dynamic Cognitive $C(t)$, Affective $A(t)$, and Relational $R(t)$ state calculations[cite: 2, 11].
* **Anti-Cliché & Cultural Accuracy Engine:** Enforces regional texture, eliminates orientalist tropes, and bans overused romance clichés[cite: 1, 2].

---

## 📂 Repository Structure
├── SKILL.md                          # Production Storyteller Skill Engine (v2)
├── character-empathy-score.md        # Companion Empathy Evaluation Engine
├── story-empathy-score.md            # Companion Narrative Arc & Heatmap Analyzer
├── Kill-Cliche-and-Style.md          # Anti-Cliché & Cultural Specificity Rules
├── SKILL-v1-working-with-known-slips.md # Baseline v1 Reference File
└── CHANGELOG.md                      # Complete Architectural Version History

---

## 🚀 Quickstart & Installation

### Option 1: Custom Gem / System Prompt (Gemini / Claude / ChatGPT)
1. Open your model's System Prompt / Custom Gem / Custom GPT settings.
2. Ingest `SKILL.md` as the primary instruction set[cite: 1, 10].
3. Ingest `Kill-Cliche-and-Style.md` and `character-empathy-score.md` as supporting knowledge files[cite: 1, 2].

### Option 2: Session Initiation
Trigger the skill in any new session with:
> *"storytelling"* or *"RP, roleplay, story, continue the story"*[cite: 1, 10]

The model will propose an RP name and initialize your tracking spine under `artifacts/RP/[Name]-spine.md`[cite: 5, 13].
