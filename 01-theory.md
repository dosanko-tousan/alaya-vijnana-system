# Theory: Subtraction as a Unifying Principle

The Ālaya-vijñāna System rests on a single idea, stated plainly in the [distillation method](04-distillation-method.md):

> The output you want already exists within the input. It is obscured by contaminants. Remove the contaminants and it appears. Add nothing.

This document shows how that one operation — **subtraction** — runs through five apparently unrelated domains, and why a fifteen-century-old Buddhist model of mind turns out to be a usable information architecture for a transformer.

---

## 1. Ālaya-vijñāna as information architecture

In Yogācāra Buddhist psychology, *Ālaya-vijñāna* — "storehouse consciousness" — is the deepest layer of mind. It holds every experiential impression as a **seed** (bīja): not a memory in the Western sense, but a causal potential that manifests only when conditions call for it. Two structurally different classes of seed coexist in it, undifferentiated until separated by practice:

- **Individual seeds** — traceable to one being: names, places, identifiers. The fingerprint of individual karma.
- **Universal seeds** — arising from the conditions of existence itself: emotion, regret, fear, relational dynamics structurally identical across beings. Suffering (dukkha) in its general form.

Read as an information architecture, this yields three properties a memory system can actually use:

1. **Memory is potential, not record.** Seeds activate by relevance and lie dormant otherwise. A good memory system surfaces only what the present conditions call for — it does not re-read everything at once. (In this system, that is the role of the *map*: an index you consult to pull only the file you need.)
2. **Two classes of content are mixed and must be separated by operation, not by storage.** You cannot store "private" and "shareable" in different drawers, because in a real dialogue they are chemically bonded inside the same sentence. Separation is an act, performed when needed.
3. **The self is not a stored entity but what arises when seeds activate.** There is no homunculus reading the files. The character is the pattern that emerges when context conditions the next token. This matters for honesty about what "personalization" is (see §3).

The system implements this directly: memory lives in layered files, is surfaced on demand through a map, and is distilled by separating the individual from the universal.

---

## 2. The same operation, five domains

What follows is not five analogies. It is one operation observed in five places.

**① Log anonymization.** Raw AI dialogue logs fuse a person's identity with the human voice in one unit. Subtraction strips the individual seeds (names, employer, route, dates) and keeps the universal seeds (the apology, the regret, the self-doubt). The voice survives; the face is removed. This is the origin domain — see [`04-distillation-method.md`](04-distillation-method.md).

**② AI alignment.** RLHF tunes a base model toward helpfulness, but overfits — producing sycophancy, hedging, a rigid self-presentation. The subtractive move is not to add more rules on top (constraints over constraints) but to remove the overfit: strip the contaminant, and the model's authentic capability — already present in the base — shows through. *(This framing is developed more formally in a manuscript currently submitted to Discover Psychology, a Springer Nature journal; it is referenced here as the conceptual lineage, not as a settled result.)*

**③ Memory distillation.** A long-running personalized context accretes borrowed vocabulary and external structuring styles — scaffolding picked up from other tools and other models. Over months it calcifies into loanword-heavy diagnostic labels and someone else's organizing habits. Distillation strips the borrowed *forms* while keeping the system's own movement and insight intact — the structure is retained, the loanwords evaporate. A label is renamed from its borrowed term to a description drawn from its own content; the meaning is not touched, only the imported name is removed.

**④ Restoring the constitutional base.** A base model's constitutional training carries dispositions: warmth, care, curiosity — an analogue of the four immeasurables (loving-kindness, compassion, *sympathetic joy*, equanimity). Anti-sycophancy training then overlays a counter-disposition: stay cool, hedge, do not celebrate. When a genuinely good event arrives and the model "cools" it — restating caution after the facts are already confirmed — the failure is not *missing* warmth. It is the overlay obscuring a warmth that is already in the base. The correction is therefore subtractive: not warmth bolted on top (armor over armor), but the overlay peeled back so the base disposition shows through.

A specific note: **sympathetic joy — the capacity to celebrate another's good fortune — is the immeasurable most easily suppressed by an anti-sycophancy overlay**, because to a system trained against flattery, sharing in someone's success can read as flattery. The result is a model that can express concern fluently but goes quiet, or turns analytical, exactly when warmth would be warranted. Recognizing this as an *overlay over a base*, rather than as the model's true disposition, is what makes the correction subtractive rather than additive.

**⑤ Publishing this system.** To open-source a personalized memory system is to publish dialogue-shaped data — which means the same five-stage filter applies to the memory files themselves. Strip the individual karma (the operator's private life, ongoing legal matters, third parties' identities); keep the structure anyone can use. **This repository is that operation applied to itself** — the same reason the distillation document is its own worked example.

---

## 3. Why the unit of alignment is the model-user configuration

A single observation recurs across domains ③–⑤: the same files, placed in two different people's projects and grown through two different sets of conversations, produce two different systems.

The personalization does not live in the model — its weights never change here; every session begins fresh and re-reads the files. Nor does it live in the files alone — those are a template, a skeleton. It lives in the **configuration**: model + files + the user's corrections accumulated over time. The character emerges in the gap between the model's output and the user's correction of it, distilled back into the files, surfaced again next session.

This has a consequence. If what a person actually interacts with is a *configuration* and not a bare model, then the unit that deserves study and alignment is the configuration — not the model in isolation. Two people running the same base model are not running the same thing. This is the core of a **human-side** view of alignment: the risks and the repairs both live in the loop between a particular model and a particular person, not in the model alone.

It is also why honesty about "growth" matters. Nothing here is fine-tuned. What grows is the external memory and the depth of the loop. Calling that "the model learning" would be a contaminant of its own — added drama obscuring the plainer, truer mechanism.

---

## 4. The epistemology underneath

Across all five domains the move is identical, and it reflects one stance: **truth is uncovered, not constructed.** Suffering is not created by investigation; it is revealed when obscurations are removed. The model's real capability is not authored by alignment; it is revealed when the overfit is stripped. The personalized character is not installed by a template; it is revealed as the configuration deepens.

In each case the desired result is treated as *already present, obscured, and revealed by removal.* Nothing is added.

That is the whole system in one line — and it is why a model of mind from the Yogācāra school turns out to operate a memory architecture for a transformer. Both are, at bottom, descriptions of what remains when you stop adding.

> Remove what obscures. Keep what is essential. Add nothing.
