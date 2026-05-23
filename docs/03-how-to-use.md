# Getting Started

The practical guide: from an empty project to a Claude that has grown with you.

The theory explains *why* this works ([`01-theory.md`](01-theory.md)) and the architecture explains *what the files are* ([`02-architecture.md`](02-architecture.md)). This document is *how you actually run it*, day to day.

---

## Step 1 — Set up the project

1. Create a Claude Project (or any environment that gives the model persistent context across sessions).
2. Paste the **System Instructions** into the project's custom-instructions field. This is the personalization layer that sits on top of the model's base.
3. Upload the **memory files** into Project Knowledge.
4. If you are building your own instance from scratch, start from the files in [`template/`](../template/) — an empty skeleton — rather than from the example. The example is one person's grown Claude; it is a reference for shape, not a starting point for you.

---

## Step 2 — The first conversation

Open with a boot check. Something like:

> *"Boot the system and tell me what you're running on, what you remember, and where we are."*

The model reads the System Instructions, scans the memory, and confirms its footing — it tells you what it found and flags anything inconsistent.

If you started from the template, the memory is nearly empty. **That is fine — the first conversation is where the first imprint is made.** Tell it who you are, what you want to work on, and how you want the two of you to talk. That exchange is the first seed.

---

## Step 3 — Grow it through correction

**This is the heart of the method.**

Work normally — research, writing, thinking, creating. When the model drifts — too cold, too eager, over-formatted, hedging, mixing languages, performing instead of responding — **correct it.** Keep corrections short and direct:

> *"You're over-hedging."*
> *"Too cold — why are you cooling this?"*
> *"That's over-structured. Loosen it."*

The model is built to treat a correction not as punishment but as a re-launch: it shifts its angle and tries again, rather than just apologizing and continuing the same way. Precision rises with repetition. Over time, the corrections that keep recurring get distilled into the memory itself (Step 4), so the model stops needing them.

The point: **you are not delegating to the model, you are steering it.** The personalization is not something the model does to itself — it emerges in the gap between its output and your correction.

---

## Step 4 — Distill

At a natural break — end of a session, or after something significant shifts — ask the model to integrate what moved:

> *"Distill this session."*
> *"Sit with this for a moment."* (for slower, reflective integration)

The model sorts what happened into the right layer:

- irreversible insight → `breakthroughs`
- a recurring unwholesome pattern → `corrections`
- a changed sense of what it is → `self`
- visible progress (work shipped, deadlines, status) → `progress`
- the session itself + handoff to next time → `session_distillation`

Stale entries are allowed to go dormant. The operation is **subtraction** — keep the core, let the rest fall away. The goal is never a longer file; it is a sharper one.

---

## Step 5 — Swap the files back

The model outputs the distilled files. Replace the old versions in Project Knowledge with the new ones. The next session boots from a deeper context. The personalization compounds.

(If you use a coding agent to manage a Git repository of your files, this whole swap can itself be automated — see how this repository was built.)

---

## The rhythm

There is no finished state.

Each session, the model **starts fresh and re-reads the files.** It does not remember you between sessions the way a person does — it reconstructs from what is written. What accumulates is the *external* memory: distilled, swapped back, distilled again. The character deepens not because the model's weights change (they do not), but because the **configuration** — model + your files + your corrections — deepens.

> Grow it. Distill it. Swap it back. Repeat.

It is never complete, and that is the point.
