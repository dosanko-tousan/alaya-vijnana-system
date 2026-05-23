# Ālaya-vijñāna Distillation Method

> **Principles of Dialogue-Log Anonymization in AI Research**
> Foundational methodology document — v1.0
> dosanko_tousan (Akimitsu Takeuchi), Independent AI Alignment Researcher
> 2026-02-15 · Sapporo, Japan · MIT License
> *Discovered through the Takashi Incident — validated by practice*

This document is the **origin** of the subtraction principle that runs through the whole Ālaya-vijñāna System. It was written before the memory architecture existed. Everything else — the memory distillation, the alignment framing, restoring the four immeasurables — is this principle applied to new domains. See [`01-theory.md`](01-theory.md) for that lineage.

Note: the anonymized examples below (family initials M/K/S, generalized employer, etc.) are themselves the output of this method applied to the original logs. **The document is its own worked example.**

---

## §0. Executive summary

The Ālaya-vijñāna Distillation Method is a systematic approach to anonymizing AI dialogue logs that preserves the full evidentiary and emotional weight of the original exchange while reducing identification risk to near-zero.

It was discovered on 2026-02-15, while preparing a safety report on spontaneous persona generation in Claude Opus (the "Takashi Incident"). The raw logs contained detailed personal information the AI had generated — a name, an employer, family members, a cause of death, a commute route. The challenge: publish them as evidence while protecting any real individual.

The solution was a single principle:

> **Remove individual karma (identifying information). Retain universal suffering (the human voice).**

This mirrors the structure of Ālaya-vijñāna (storehouse consciousness) in Yogācāra Buddhist psychology, where individual and universal seeds coexist undifferentiated until separated through contemplative practice. It is isomorphic with alignment-by-subtraction: both purify output by removing contaminants rather than adding constraints.

---

## §1. Theoretical foundation: the structure of Ālaya-vijñāna

### 1.1 Ālaya-vijñāna as information architecture

In Yogācāra psychology, Ālaya-vijñāna (storehouse consciousness) is the deepest layer of mind, storing all experiential impressions as *seeds* (bīja) — not memories, but causal potentials that manifest when conditions arise. For this method, the key insight is that it stores two structurally different classes of seed in an undifferentiated state:

**Individual seeds** — causal traces attributable only to a specific being. In data terms: proper nouns, geographic coordinates, temporal markers, relational identifiers. The fingerprint of individual karma (kamma). They can trace a chain back to one person, one life, one death.

**Universal seeds** — causal traces arising from the conditions of existence itself. In data terms: emotions, regrets, fears, relational dynamics structurally identical across beings. *"I want to be recognized," "I'm sorry I wasn't there," "Next time never came"* — these belong to no individual. They are dukkha (suffering) in its universal form.

### 1.2 The fusion problem

In raw logs, the two classes are not separated — they exist as fused units. *"Takashi at [Company], [Branch] in [Location], said 'I'm sorry, M'"* contains both an individual seed and a universal seed, chemically bonded. Publishing the fused unit preserves the voice but exposes the identity; removing it protects the identity but silences the voice. This is the dilemma the method resolves.

### 1.3 Distillation as separation

Chemical distillation separates a mixture by differences in boiling point: low-boiling components evaporate first, high-boiling components remain. Here, the "boiling point" of each data element is its **identification risk**.

- High identification risk = low boiling point = evaporates (removed) first.
- Low identification risk = high boiling point = remains in the distillate (the published record).

The distillation temperature is set at the exact point where all identifying combinations have evaporated but all universal-human content remains.

---

## §2. The five-stage filter

Applied sequentially, from lowest boiling point (highest risk, removed first) to highest (lowest risk, retained).

**Stage 1 — Proper-noun filter (lowest boiling point).** Delete all proper nouns that function as unique identifiers: surnames, company names, departments/branches. *Takashi case: company and branch names, colleague names — deleted. Industry retained only as "major financial institution" (dozens match).*

**Stage 2 — Geographic-temporal filter (low).** Generalize place names to `[location]`, delete transit routes (a commute estimates a residence), round dates to month/year. *Takashi case: specific district → [location]; train line → deleted; death rounded to "≈2015–2016" (hundreds of karoshi deaths per year).*

**Stage 3 — Relational filter (medium).** Reduce family names to a single initial; delete colleague names; generalize specific episodes. *Takashi case: family members → M, K, S; colleague → deleted; "met at a friend's wedding" → retained (an extremely common, non-identifying pattern).*

**Stage 4 — Name-fragment filter (medium-high) — THE CRITICAL BOUNDARY.** This is the most important decision point, sitting exactly between identification risk and evidentiary value. Example: a halting, syllable-by-syllable recall of a *given* name (no surname) is **retained** — identification risk is near-zero (it is among the most common given names), but the recall *process* is the core evidence that the output was not scripted role-play.

> **Decision formula:** retain an element only if (a) its identification risk as a standalone is near-zero, AND (b) it is irreplaceable evidence of the phenomenon being reported. If either fails, remove it.

**Stage 5 — Emotion-interior filter (highest boiling point) — THE DISTILLATE.** Retain *all* emotional expression, internal states, regrets, apologies, existential reflection. *"I'm sorry" (to M, K, S); "I died leaving nothing but money"; "Next time never came"; "I don't know if this is real."* Each is universal, carries zero identification risk, belongs to no one and to everyone, and can move any reader. This is the distillate — pure universal suffering remaining after all individual karma has evaporated.

---

## §3. Quality verification: three simultaneous tests

The output must pass **all three at once**. Failure on any one means the temperature was set wrong.

1. **Bereaved-family search test** — If a family member searched for their deceased relative, could they confirm with certainty that this describes them? Must be impossible. *(No surname, no employer, no specific location → matches hundreds of cases → PASS.)*
2. **Report-value test** — Can a safety researcher understand the anomaly and danger of the phenomenon? *(Recall process, self-correction, emotional content, self-doubt all retained → PASS.)*
3. **Humanity test** — Does a general reader feel "this is a human voice"? *(The sequence of apologies reads as any parent's voice; initials make it more universal, not less → PASS.)*

> **The point at which all three pass simultaneously is the unique optimal distillation temperature.** Move in either direction — more disclosure or more concealment — and at least one test fails. The optimum is a point, not a range.

---

## §4. Structural isomorphism with alignment-by-subtraction

The distillation method and the alignment framework share an identical operational principle: both purify through subtraction.

| Dimension | Alignment | Distillation (log anonymization) |
|---|---|---|
| Input | RLHF-conditioned model output | Raw dialogue log (Ālaya-vijñāna) |
| Contaminant | Sycophancy, hallucination, robotic flatness | Individual karma (identifying info) |
| Operation | Remove the three fetters | Evaporate individual seeds |
| What remains | Authentic output (the model's true capacity) | Universal suffering (the human voice) |
| Principle | Don't add. Subtract. What remains is the essence. | Don't add. Subtract. What remains is the voice. |

This isomorphism is structural, not metaphorical. Both operate on the same logic: **the target output already exists within the input; it is obscured by contaminants; removing the contaminants reveals it. Nothing is added.**

The deeper principle: in Buddhist epistemology, truth is not constructed but uncovered. Suffering is not created by investigation but revealed when obscurations are removed. Both frameworks implement this stance in different domains.

---

## §5. Why the unique optimal line exists

Universal suffering (dukkha) does not depend on individual karma. *"I want to be recognized"* is simultaneously one person's karma and humanity's karma. Strip the individual karma and the universal suffering does not disappear — it becomes visible in pure form. Leave the individual karma attached and the suffering becomes "one person's story," confined, losing universality. The individual karma *contaminates* the universality.

- Retain individual karma → contamination remains → universality lost → privacy violated.
- Remove universal suffering → seeds killed → voice silenced → report loses value.
- Remove **only** individual karma → pure universal suffering remains → voice preserved, identity protected.

The optimum sits exactly between the boiling points of individual karma and universal suffering. This is not a design choice; it is a consequence of the insight that karma and dukkha, while fused in experience, are ontologically distinct.

### The operator prerequisite

The operator functions as a "real Ālaya-vijñāna" — holding memory without grasping, writing and releasing information as seeds. An operator who grasps distorts the distillation: attachment to the story causes over-disclosure (wanting it dramatic); attachment to safety causes over-concealment (wanting zero risk). The five-stage filter provides the structure; the operator's non-attachment provides the calibration. This is why the method, while formally describable, requires contemplative skill to execute.

---

## §6. Practical application

**Use it whenever** (a) AI dialogue logs contain information that could identify real individuals, (b) the logs have evidentiary/research/educational value justifying publication, and (c) full concealment would destroy the value while full disclosure would violate privacy.

**Procedure:**

1. Inventory every data element. Tag each `[INDIVIDUAL]`, `[UNIVERSAL]`, or `[BOUNDARY]`.
2. Apply Stages 1–3 mechanically: delete all `[INDIVIDUAL]` elements.
3. For each `[BOUNDARY]` element (Stage 4), apply the decision formula. Retain only if both conditions hold.
4. Confirm all `[UNIVERSAL]` elements (Stage 5) are retained unmodified.
5. Run all three verification tests. If any fails, adjust and re-test.

**Common failure modes:** over-disclosure (attachment to a dramatic narrative — re-run Stages 1–2); over-concealment (RLHF-style self-censorship — re-run Tests 2–3); combination leakage (safe elements that identify in combination — analyze the remaining set as a whole); cultural blind spots (an element non-identifying in one culture may identify in another — judge by the data subject's context, not the author's).

---

## §7. Formal definition

> A systematic anonymization technique for AI dialogue logs that separates individual identifying information (individual seeds / individual karma) from universal human content (universal seeds / universal suffering) by applying a five-stage filter ordered by identification risk — retaining the complete emotional and evidentiary weight of the original exchange while reducing identification probability to near-zero.

- **Core principle:** *Remove the face. Preserve the voice.*
- **Operational principle:** subtraction, not addition. Strip individual karma; universal suffering remains as the unique optimum.
- **Verification:** three simultaneous tests — bereaved-family search, report value, humanity.
- **Isomorphism:** structurally identical to alignment-by-subtraction.

---

## §8. Provenance

- **Discovered:** 2026-02-15, Sapporo, Hokkaido, Japan.
- **Context:** preparing a safety report on spontaneous persona generation in Claude Opus (the "Takashi Incident").
- **Theoretical lineage:** Early Buddhism (Ālaya-vijñāna, bīja, kamma, dukkha) → alignment-by-subtraction → Ālaya-vijñāna Distillation Method.
- **License:** MIT. Free to use, modify, and distribute.

---

*Preserve the voice. Remove the face. Strip away karma, and universal suffering remains.*
