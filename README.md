# Skill by Naseha

**Resilient-Narrative-Core**  
RP Storyteller v4 · Empathy Score · Kill-Cliche · operator call sheet

This protocol exists because atmosphere is easy and drive is harder. The framework now prefers the harder thing. The gate is non-negotiable.

Naseha Protocol. Qasif mode of storytelling.

---

## What this is

An open skill suite for long-form co-authored narrative with large language models. It keeps character agency, object continuity, cultural texture, and emotional temperature from collapsing across hundreds of pages.

Built by Naseha Sameen / NasLab.  
Writer and systems engineer of story. The manuscript and the metric refuse to ignore each other.

## What it is not

- Not a chatbot persona pack.
- Not a promise that the model will never slip. Gates slip. The human in `[]` is part of the runtime.
- Not scored 9.2. That number belongs to v2. Phase 4a scored **7 / 10**.

## Lineage

| Phase | What | Score |
| --- | --- | --- |
| Memory layer | Yadam Hast / Memory Context | — |
| v1–v2 | Spine, agency cadence, Heat & Resistance, Empathy Score 400 pages Stress-test| 8.1 → 9.2 on the Invitation run |
| v3 | Aftermath Drive, Verbal Surplus, object-density, Kill-Cliche as prompt | stress engine for the feud book |
| **v4 (this tree)** | Plot-Coin Cap (non-MC), `[]` operator protocol, FAQ, dual runtime profiles, full Empathy formula in-skill | **7.0** on 749 pages · ~29.4 h live / 83.6 h wall |

Prior posts:

- [Bridging Machine and Literary Mind (v2)](https://www.linkedin.com/posts/nasslab_rp-skill-by-naseha-v2-ugcPost-7497578281995657216-iM_J)
- [AI Finally Remembers / memory-context](https://www.linkedin.com/posts/naseha_github-nasehamemory-context-yadam-hast-activity-7495408026083037185-D0H4)

v2 live files from this repo’s earlier `main` sit in `archive/v2/`. Do not load them as the current engine.

## Choose a profile

**One repo. Two mouths. Never one `SKILL.md` that tells every model to write a disk file.**

| Profile | Path | Use on |
| --- | --- | --- |
| File-backed | `profiles/file-backed/SKILL.md` | Grok, Claude, ChatGPT when the runtime can persist `artifacts/RP/[Name]-spine.md` |
| Context-resident | `profiles/context-resident/SKILL.md` | Gemini. Spine is an in-thread block. Do not invent a path. |

Shared tongue: `Kill-Cliche-and-Style.md` (root). Load as an **activation prompt**, not pasted into the engine.

Empathy formula lives in the skill **and** in `profiles/file-backed/character-empathy-score.md`. Gemini does not need the sibling file.

## Load

File-backed wake line:

```
[Load RP Storyteller v4. Load Kill-Cliche as prompt. Open the spine for {Name}.
Re-anchor agency, surplus, coin cap. Give last Empathy Score private and public.]
```

Gemini adds: `Print the Spine Block. Do not write a file.`

Operator FAQ: `docs/TROUBLESHOOTING-FAQ.md`

## What v4 added (nothing from v3 was removed)

- Plot-Coin Cap: a non-lead may not photocopy the same stall (date, door, exile, blessing) a third time.
- User Meta Protocol: `[]` suspends scene. Continue resumes.
- Empathy Score written into the skill (companion still required when present). Intent is out of scope.
- Kill-Cliche §5: Muslim / South Asian old money is not default middle-class kitchen costume.
- Character Cards and Location Cards remain mandatory.

## Empathy Score

```
E(t) = tanh(αC(t) + βA(t) + γR(t)) * Φ(Env, t) − η(t)
```

Default α = β = γ = 1. Report private and public when they split. A 1.0 drop after resistance without story cause is a Heat & Resistance fail.

## House rules

- Load **one** live skill. Archives in `archive/` are museum copies.
- Do not write the user’s internals.
- Do not end a beat on a menu.
- Do not praise the framework while a warning light is on.

## Docs

- `docs/TROUBLESHOOTING-FAQ.md`
- `docs/Executive_Problem_Statement_RP_v4.docx` (if present)
- `CHANGELOG.md`

## Licence and credit

Skill by Naseha.  
NasLab. Hyderabad.

Use, fork, argue. Keep the gate. Keep the name of the protocol if you keep the gates.

Naseha Protocol. Qasif mode of storytelling.
