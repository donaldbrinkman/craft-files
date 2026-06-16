# The writing-craft scaffold: sequencing and calibrating the files

*These craft files are not a checklist. They are a pipeline, and they work best applied in an order, each one doing a job the next one depends on. This document explains that order (the scaffold), how to tune the files' examples to your own world (calibration), and how the two fit into a small model you can use to assemble a custom writing system of your own.*

*This is groundwork, not a finished product. It defines the model, the default sequence, and the calibration format, with one worked example. The automation that would compile it into a turnkey system is deliberately left for later.*

---

## The three layers

A working writing system has three separable parts. Keeping them separate is what lets the craft generalize while the specifics stay yours.

1. **The base files.** The craft itself: the figures, the passes, the structures. Universal and stable. These are the files in this library, written with neutral examples so anyone can use them. This is the part that does not change between users.

2. **The sequence scaffold.** Which file applies at which stage, and in what order. This is orchestration, not craft. Most of it is the same for everyone (the pipeline below), but you can add, drop, or reorder stages as you add your own files.

3. **The calibration mapping.** Your domain, your register, your examples. This is the part that is entirely yours: a thin overlay that tells an assistant to illustrate the universal techniques using your world and your voice instead of the generic examples in the files.

Your custom system is the base files, plus your scaffold, plus your calibration. Change the calibration and the same base library serves a different writer. That is the whole point of keeping the three apart.

---

## The sequence scaffold

The default order. Each stage names the file or files that do its work. The order is a logic, not a lockstep, and the note after it explains where it bends.

0. **Generate.** Goldberg, first thoughts. Get raw material onto the page: wide, specific, unhedged. Quality is not this stage's job.

1. **Find the point.** McDonald, the armature. Decide, or discover in the raw material, the single thing the piece is built to prove.

2. **Structure.** Truby, the seven steps. Shape the arc, the reader's journey, to serve the point.

3. **Flow.** Williams, cohesion. Make the prose read as written rather than assembled.

4. **Intensify.** Forsyth, the surprise family and the repetition family. Make the load-bearing moments land harder than plain prose would.

5. **Cut.** Orwell, the six rules. The final edit: remove what is not earning its place.

6. **Continuity scan.** Gardner, the continuous dream. A last read for anything that wakes the reader: a register slip, a tonal lurch, a factual snag.

Running underneath, not a single stage: **the attention layer.** The storytelling-and-attention file is the engagement logic, the curiosity loops, that should be live from the moment you have a point through every prose pass. Consult it whenever a piece is structurally sound but inert.

**Where the order bends.** Stages zero through two interleave by temperament. A dump-first writer generates raw material and then finds the point and structure inside it, which is the order above. An outline-first writer reverses them: settle the point and the arc, then generate prose to that shape. Both are valid, and the rest of the pipeline (flow, intensify, cut, continuity) runs the same either way. What does not bend: cut comes late, and you do not edit while you generate.

---

## Editing judgment: what to cut, what to keep

The cut and review stages need judgment, not just rules. Two things live here. One is settled; the other is being tried.

**Interesting-but-failed (principle).** When you cut, distinguish a real attempt at technique that missed from bland filler that never tried. They are not the same, and a process that cuts both with equal speed drifts toward prose that is clean and lifeless, the safe middle that offends no one and moves no one. A brave miss is closer to good than the competent average is, because it can be repaired where the average can only be tolerated. So flag the interesting failure as something to fix, not something to remove. This is the main defense against the failure mode every AI-assisted writing process drifts into: converging on the safe and the average, because that is the easiest thing to produce and the hardest to object to.

**The cut list (experimental).** *Live for use now, to be questioned at the next revision of this document.*

The cut list is a vocabulary of judgment categories for one specific mode: annotating a draft with named judgments instead of rewriting it. When that is what you want, an assistant marks spans of the draft with a category and a short note and leaves the prose alone, so you keep authorship and decide what to act on.

Categories that mark something to cut:

- **Throat-clearing.** Warm-up sentences before the real start.
- **Hedging.** Qualifiers that drain a claim of its force.
- **Over-explanation.** Spelling out what the reader would reach on their own.
- **Generic phrasing.** A line anyone could have written.
- **Over-figuration.** A figure doing decoration, not work.
- **Wrong register.** A sentence in the wrong voice for its surroundings.
- **Telegraphed setup.** A plant so visible it gives the payoff away.
- **Orphaned plant.** A setup that never pays off.
- **Forced callback.** A payoff with no real plant behind it.
- **Padding.** Words present only to fill space.
- **Wrong direction.** A passage pursuing the wrong point. Structural, not local.
- **Interesting-but-failed.** A real attempt that missed. The one category already promoted to canon above; flag it to repair, not to remove.

Categories for a span worth keeping but changing:

- **Same content, better phrasing.**
- **Different content, same function.**
- **Compression.**
- **Expansion.**
- **Reorganization.**

The plant-and-callback categories (telegraphed, orphaned, forced) are the failure modes the salience principle describes; see the storytelling-and-attention file.

At the next revision of this document, decide whether the cut list has earned promotion to canon, deserves more experimenting, or should be dropped.

---

## The calibration mapping

A calibration overlay is a short file that re-skins the universal examples to your world. It does not rewrite the craft; it tells an assistant what register and domain to illustrate the craft in. A complete overlay has five parts:

- **Domain.** The world the writing lives in: the subject, the recurring scenarios, the nouns, so examples can be drawn from your work instead of from generic ones.
- **Register and voice.** How formal or casual, the tone, any voice signatures or habits to keep.
- **Reserved vocabulary.** Words and terms to prefer, and words to avoid. The avoid-list matters as much as the prefer-list.
- **Audience.** Who the writing is for, in a line or two.
- **Exemplar swaps.** Two or three worked examples: take a generic example from a base file and show its calibrated version. These teach the assistant the kind of re-skinning you want better than any instruction.

**How to use it.** Drop the base files and your calibration overlay into the assistant's context together, with one instruction: apply the techniques in the craft files, but when you illustrate them, use the domain, register, and vocabulary in the calibration file rather than the generic examples. No overlay, and the universal examples stand. Overlay present, and the assistant calibrates to you.

---

## A worked example calibration

A calibration overlay for a small software company's engineering blog, to show the format filled in:

- **Domain.** A business software product. Recurring scenarios: shipping releases, writing postmortems on incidents, explaining the tradeoffs behind a feature, sharing what the team learned. Nouns: the product, the release, the incident, the on-call rotation, the customer.
- **Register and voice.** Plain and candid. Technical but human. Willing to admit fault. No marketing gloss.
- **Reserved vocabulary.** Prefer plain verbs: use, build, ship, break, fix. Avoid "leverage," "synergy," "robust," "seamless," "delight." Never call an outage a "learning opportunity."
- **Audience.** Working engineers and the technically literate, not executives.
- **Exemplar swaps.**
  - The surprise-family example "She was a brilliant manager, right up until anyone disagreed with her" becomes "The architecture was elegant, right up until real traffic hit it."
  - The surprise-family example "The resume opens the door. The interview decides whether you walk through it" becomes "The demo gets you the pilot. The first on-call week decides whether you keep the account."

That overlay plus the base files would yield craft examples drawn from the world of a software blog, in its voice, without anyone touching the underlying craft.

---

## Building your own system

Pick the base files you want. Use the default sequence above, or adjust it as you add files. Write a calibration overlay for your world using the five-part format. That is the system: base, plus scaffold, plus calibration.

**Conventions that keep this forward-compatible.** Base files keep neutral examples and stay free of any one domain. Calibration lives in its own file, never baked into a base file. The sequence is described, not hard-coded into the files. Following these now means a future build step could compile base plus calibration into fixed, pre-calibrated files without any of the files needing to change.

**What is deliberately not here yet.** There is no compiler and no plug-in interface. This document is the model, the default sequence, the calibration format, and one worked example. The automation comes later, if the library proves worth it. The groundwork is what makes that automation cheap to add; building it now would be building ahead of need.

---

## One guardrail

Calibration changes examples and register. It does not change the rules that govern public writing. A domain-flavored example is fine, but anything published still follows the same standards the base files do: credit sources, do not reproduce copyrighted text, and do not let a calibration overlay reintroduce something the base files were careful to leave out. The overlay localizes the craft; it does not unlock exceptions to it.
