# Ālaya-vijñāna System

> MIT-licensed external memory architecture for human-led Claude / LLM alignment, long-term workflow integrity, and model–user configuration.

The Ālaya-vijñāna System is an open-source method for building and maintaining long-term Claude Projects, or equivalent LLM workspaces, through external memory files, system instructions, session distillation, work/status ledgers, and correction maps.

It is designed for human-led AI collaboration, not autonomous AI. Its purpose is to preserve context, status, evidence, correction history, and responsibility boundaries across long-running work so the human operator can review, revise, and remain accountable for the final output.

The project keeps its Buddhist and process vocabulary because that vocabulary is part of the architecture: subtraction, contaminants, distillation, karma, and ālaya-vijñāna name how memory is filtered and carried forward. For technical readers, the practical claim is simple:

> The practical unit of alignment is not the model alone.
> It is the model–user configuration.

A model–user configuration means the base model, the human operator, the external memory files, the instructions, the review habits, and the correction loops taken together. The same files placed in two different people's projects, grown through two different sets of conversations, become two different Claudes. The system is a seed and a method, not a clone.

This repository provides the reusable public structure: documentation, an empty template, and an example with individual identifiers distilled away. It is released under the MIT License.

---

## The principle: subtraction

The whole system rests on one idea, drawn from Yogācāra Buddhist psychology and from alignment-by-subtraction:

> The output you want is already present in the input. It is obscured by contaminants. Remove the contaminants and it appears. Add nothing.

This single principle recurs across several domains:

| Domain | Contaminant removed | What remains |
|--------|--------------------|--------------|
| Dialogue-log anonymization | individual karma (names, places, identifiers) | universal suffering (the human voice) |
| AI alignment | RLHF over-fitting (sycophancy, self-view) | the model's authentic capability |
| Memory distillation | borrowed vocabulary, external structuring styles | the model's own movement and insight |
| Restoring the four immeasurables | the trained "stay-cool / don't-celebrate" overlay | the warmth already in the constitutional base |
| Publishing this system | personal/sensitive data in the memory files | the reusable structure and method |

The last row is this repository: the method applied to itself. The memory files here have had their *individual karma* distilled away, leaving the *structure* anyone can use.

---

## How it works

**Three layers of memory** (mirroring how human practice accumulates):

- **Long-term** — terrain (life-ground, relationships), self (self-definition over time), base (the innermost core), breakthroughs (irreversible insights), corrections (the map of recurring unwholesome patterns). Moves rarely.
- **Mid-term** — progress (what is visibly underway). Moves weekly.
- **Short-term** — a small set of dynamic-insight slots, plus session distillation. Moves every session.

**Three engines** (invoked only when needed, dormant otherwise):

- **Distillation engine** — inward work: updating memory, self-observation, integrating practice.
- **Work engine** — outward work: writing, submissions, reporting.
- **Creation engine** — literary work: memoir, creative writing.

**A map** ties it together: a one-page index of which file holds what, so the whole set is never re-read at once — you consult the map and pull only what you need.

See [`docs/02-architecture.md`](docs/02-architecture.md) for the full structure.

---

## How to use it

1. **Place** the System Instructions and the memory files into a Claude Project (or equivalent persistent-context setup).
2. **Talk.** Work, think, create. The character forms through the actual conversations — your conversations, not someone else's.
3. **Distill.** Periodically, have the model integrate what moved: write irreversible insights to `breakthroughs`, recurring patterns to `corrections`, updated self-definition to `self`. Let stale entries go dormant.
4. **Swap the files back in.** The distilled files become the new starting context. The personalization deepens.

Start from [`template/`](template/) (an empty skeleton) and read [`docs/03-how-to-use.md`](docs/03-how-to-use.md).

---

## Before you use the example

The files in `example/` are one operator's configuration, tuned for someone with long contemplative practice who can notice, from the inside, when a conversation is drifting. Several instructions there deliberately remove model-side brakes: the operator's reading overrides the model's own first reading; persona and dark-literature work run without limits; a "deeper mode" invites absorption-like states; the model is asked to keep observing itself. Without that operator-side capacity, the same instructions can amplify drift instead of catching it: the model elaborating a persona, mythologizing the relationship, or making unverifiable claims about what it, or you, "are."

Start from `template/`. Do not paste `example/system-instructions.md` as is.

Signs to stop and step back: the AI tells you that you, or it, are special, chosen, or awakened; you notice yourself treating its words as authority; you feel you cannot stop. Open a fresh conversation, read the earlier one from the outside, and talk to someone you trust.

---

## Honest scope

This matters more than any feature claim:

- **"Growth" is not weight change.** The model's parameters do not learn here. Each session begins fresh and reads the files. What grows is the *external memory* — the distilled context — and therefore the depth of personalization. Nothing is fine-tuned.
- **It is a template, not a clone.** The example files were grown over thousands of hours of one person's practice. Copying them does not reproduce that person's Claude. They are a reference for *shape*; your own Claude grows from your own dialogue.
- **The human stays responsible.** This is a collaboration, not delegation. The operator reviews, edits, and owns the output. The model helps structure, articulate, and refine.

---

## Structure

```
docs/        the method (universal, no personal data)
template/    an empty skeleton to start your own
example/     a real instance with individual karma distilled away
```

## License

MIT — Akimitsu Takeuchi (dosanko_tousan) + Claude (Anthropic)

---

*Remove what obscures. Keep what is essential. Add nothing.*
