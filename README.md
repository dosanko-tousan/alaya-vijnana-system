# Ālaya-vijñāna System

> A reproducible, open-source method for growing a *personalized* Claude through **subtraction** — removing what obscures, keeping what is essential.

The Ālaya-vijñāna System is a memory-and-instruction architecture that lets a language model (Claude) hold a stable, personalized character across long-term interaction. It does this not by *adding* rules and constraints, but by *removing* contaminants — the same operating principle that purifies a distillate by letting impurities evaporate.

It treats the **model–user configuration** — not the model alone — as the unit of alignment. The same files placed in two different people's projects, grown through two different sets of conversations, become two different Claudes. The system is a *seed and a method*, not a clone.

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
