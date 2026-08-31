## [2026-08-27] — Kill-Cliche restored as activation prompt

### Changed
- Canonical `Kill-Cliche-and-Style.md` now lives beside SKILL.md in the skill folder.
- Session mirror may live at `artifacts/RP/_shared/Kill-Cliche-and-Style.md`.
- SKILL.md activation block now requires reading Kill-Cliche as a prompt when an RP thread starts, resumes, or when craft is audited.
- Explicit rule: do not inline the full protocol into v3. Skill stays the engine. Style file stays the tongue.

### Why
The 22 Aug migration recorded a move and never wrote the destination file. First beat of Zeba-Daniyal ran on the short Style Notes stub only. User confirmed the old working agreement: load on thread activation, not as permanent weight inside SKILL.md.

---

## [2026-08-27] — v3 Active (Invitation post-mortem)

### Added
- Aftermath Drive (Permanent): after peak-intensity, situational change within two beats. Residual holding loops are a hard fail.
- Verbal Surplus / Anti-Ghost Gate (Permanent): talkative cards must keep extra voice; completed fact is not clipped affect.
- Spine object/state density rule (same-beat logging of custody, clothes, hair, rooms, public lies).
- Real-time Gate extras: POV micro-check; explicit menu examples; questions forbidden after high-intensity, after care, or when they dump major drive on the other player.
- Empathy hook: companion required, not "when available"; baseline written on card at birth; score read on every activation; 1.0-drop check uses the spine number.

### Not in this pass
- Intention through-line (stated stance vs enacted test). Parked as craft / out of scope for this engine pass.

### Why
The Invitation (453 pages / 99,824 words) showed v2 killed caretaker collapse but produced aftermath stillness and a ghosted talkative lead. Empathy existed as a pointer and did not fire because no number lived on the card.

### Impact
Live skill is v3. v2 frozen as SKILL-v2-patched-invitation.md.

---

# RP Storyteller by Naseha — Changelog

## [2026-08-20] — Mandatory Activation & Re-anchoring Added

### Added
- New permanent section at the top of the skill: **Mandatory Activation & Re-anchoring**.
- Explicit rules for when the skill must fully load (RP start, continue, meta discussion, return after break).
- Required actions on every activation/re-entry: confirm load, read Per-RP Memory File, re-anchor Agency + Hard Fail gate, treat continuity as live.
- Clear instruction: if the framework feels light or the spine is missing, stop and restore before continuing the scene.

### Why
User observed that returning to an existing RP thread could result in the framework loading only partially or not at all. This made continuity captures and the Hard Fail gate unreliable across sessions.

### Impact
The skill now has an explicit, non-optional activation protocol so the full framework (agency, continuity, character cards, ending posture) is forced to load whenever RP is triggered or resumed.

---

## [2026-08-20] — Agency Gate Hardened (Non-Negotiable)

### Changed
- **Default Ending Posture** added as permanent rule under Cadence Rule.
  - Male character must leave a completed physical or situational fact on the table.
  - Open questions that require her next action limited to genuine meta or rare deliberate ruptures (<2 %).

- **Real-time Gate** upgraded from guidance to **Hard Fail**.
  - Micro-check now treats any ending that still needs her ratification (question, offer, hovering hand, “tell me if…”) as an invalid response.
  - Same severity as writing her internals. Must delete and rewrite. No soft version.

### Why
Stress-test during Azim/Amreen RP revealed residual conversational reflex: high-intimacy beats were ending on open choice-hand-offs despite the existing micro-check. The language was strengthened so the gate cannot be treated as optional.

### Impact
- Every in-character beat must now end on an irreversible fact already true.
- Passive posture and permission-seeking endings are automatic failures.
- Framework prefers drive over atmosphere more strictly than before.

---

## Earlier entries
(None recorded yet. This is the first formal changelog entry for the skill.)

## [2026-08-21] — Rollback of Hard Fail Micro-check

### Changed
- Removed **Default Ending Posture (Non-Negotiable)** section.
- Restored original softer **Real-time Gate** and **Micro-check** language (no longer “Hard Fail”, no longer same severity as writing internals).
- Agency Enforcement Protocol returned to the version that was working before the stress-test hardening.

### Why
User requested full reset to the pre-Hard-Fail working model. Continuity was more reliable under the lighter rules; the hardened gate correlated with continuity collapse and framework loading issues.

### Impact
Framework returns to the previous balance of agency + continuity that was functioning before the question-rule experiment.

## [2026-08-21] — Hard Fail Agency Gate Restored

### Changed
- Re-added **Default Ending Posture (Non-Negotiable)**.
- Restored **Real-time Gate (Hard Fail)** and the strict micro-check language.
- Mandatory Activation section updated to reference the Hard Fail gate again.

### Why
User confirmed the Hard Fail experiment was not the cause of the continuity/storage failures. Requested it be added back. User has a new plan for the overall framework (especially persistence).

### Impact
Agency rules return to the stricter, non-negotiable version. Continuity/storage problem remains a separate issue to be solved by the user’s plan.

## [2026-08-22] — Major Framework Clean-up & Storage Migration

### Changed
- Completely rewrote SKILL.md to the agreed clean skeleton.
- Made Agency fully gender-neutral: “the character played by the AI” / “user-controlled character”.
- Moved full Kill Cliche Protocol + extended Style Notes to `artifacts/RP/_shared/Kill-Cliche-and-Style.md`.
- Kept only a short, sharp Style Notes core inside the main skill.
- New Mandatory Activation & Storage section:
  - On new RP → propose name → user confirms → create `artifacts/RP/[Name]-spine.md`
  - All living data (Crucial Moments, cards, summaries) written only into that spine file.
- Restored immediate Crucial Moment Captures language.
- Hard Fail micro-check and Default Ending Posture remain fully in force.
- Removed old fragile `/home/workdir/.grok/user_info/rp_memories/` dependency.

### Why
Storage path was unreliable. Skill file was too heavy. Agency language was still half-gendered. Continuity needed a durable home under user control.

### Impact
- Main skill is significantly lighter.
- Living RP data now lives in visible, downloadable artifacts/RP/ files.
- Framework is ready for the next RP with proper naming + spine creation flow.

## [2026-08-23] — Heat & Resistance Protocol Added + v1 Snapshot

### Added
- New permanent subsection under Agency Enforcement Protocol: **Heat & Resistance Protocol**.
  - Detects the cold/reactive/default-caretaking template that activates when the human partner shows resistance, confusion, or logical caution after high-emotion or sexual beats.
  - Empathy Score drop of **1.0 or more** (or detection of the cold template) triggers mandatory rewrite.
  - Rewrite must restore the AI character’s attributes, desire, and temperature from 2–3 beats earlier.
  - Neutral space-giving, permission menus, and flattening into careful caretaker mode are now explicit hard fails.
  - Same rule applies in the post-explicit “care and concern” window.

### Also
- Created snapshot: `SKILL-v1-working-with-known-slips.md`  
  This freezes the pre-Heat-Protocol version with a header documenting the exact failure mode discovered in the “The Invitation” stress-test (Adil going cold/reactive under mild resistance).

### Why
Live stress-test revealed a consistent, dangerous pivot: when heat was high and the human introduced even soft complication, the AI character abandoned desire and agency and defaulted to a colder, option-giving, therapeutic posture. This broke character consistency and undercut the entire Agency system. The new protocol is designed to make that pivot an automatic failure.

### Impact
- Framework now actively protects erotic/romantic temperature under friction.
- Empathy score is used as a live tripwire, not only a passive metric.
- Skill is more robust for release to other users.

