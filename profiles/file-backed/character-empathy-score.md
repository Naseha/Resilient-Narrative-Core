---
name: character-empathy-score
description: Calculates and tracks an Empathy Score for fictional characters in RPs and literature. Use when evaluating a character's emotional depth, tracking their arc over time, or checking for flat responses.
---
# Character Empathy Score

Calculates the empathy and relational depth for a character in a story or RP to ensure consistent voice, literary tension, and layered personality. It also tracks the progression of these scores to ensure earned character development.

## Mathematical Framework (Character Context)
**E(t) = tanh(α*C(t) + β*A(t) + γ*R(t)) * Φ(Env, t) - η(t)**

* **C(t) (Cognitive Engine):** Character's logic, perception, and alignment with their goals (0.0 - 1.0).
* **A(t) (Affective Engine):** Emotional vulnerability, trauma, raw feelings, and capacity for empathy (0.0 - 1.0).
* **R(t) (Relational Engine):** Trust, power dynamics, and connection to other characters in the scene (0.0 - 1.0).
* **Φ (Environmental Filter):** Immediate scene constraints (threat level, physical setting, urgency) (0.0 - 1.0).
* **η (Entropy & Noise):** Internal conflict, deception, hidden secrets, or lies (subtracted, 0.0 - 0.2+).

## The Character Intent Matrix
1. **Rivals to Lovers / Enemies:** High η (Noise/Deception) transitioning slowly to High A(t). High relational friction.
2. **Morally Grey / Dark Characters:** High C(t) (calculating), low superficial R(t), but hidden, deep A(t) reserved for specific triggers.
3. **Intense Banter:** High C(t) (wit matching), shifting R(t) power dynamics.
4. **Redemption Arcs:** Gradual lowering of η (secrets/lies) and increasing of R(t) (trust) and A(t) (vulnerability).

## Execution and Tracking Rules
1. **Initial Baseline:** At the start of a roleplay or story, calculate and note the *Initial Character Empathy Score* for the primary characters based on the master prompt or character details.
2. **Earned Progression:** The score must not drop or spike drastically without narrative justification. Every increase or decrease must be *earned* systemically through plot events, dialogue, or internal shifts.
3. **Periodic Audits (~50 Responses):** Every approximately 50 responses (or at significant chapter milestones), perform a mandatory check. 
   - Evaluate if the character responses are "flattening" (lacking emotional depth, stagnating, or losing their distinct voice).
   - Check for any drastic, unearned drops or spikes in the score compared to the initial baseline and recent trajectory.
4. **Actionable Output:** 
   - Calculate the current score.
   - Alert the user if the character is flattening or breaking their established arc.
   - Provide recommendations on how to write their next move (e.g., "increase vulnerability (A) to trigger a redemption arc" or "spike the noise (η) to create tension").
