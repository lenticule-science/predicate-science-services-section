---
name: write-computational-models-paper
specialization: task
work-type: inquiry
plan: ordering-first-computation
serves: ordering-first-computation
assigned-to: researcher
priority: high
produces: library/theories/science/theories/information/texts/predication-computing.md

read-first:
  - operations/command/personnel/emsenn/projects/writing/babbles/2026-03-28-1016h.md
  - library/theories/science/theories/information/texts/the-adjoint-structure-of-predication-on-bilattice-valued-fibers.md
  - library/theories/science/theories/relationality/terms/relating.md
  - operations/engineering/systems/fars/predication.js
status: open
---

The adjoint paper proves the algebra. The babble derives where the algebra comes from. This paper says what the algebra IS, computationally, and what that means.

## The core insight

Shannon gave communication a mathematical foundation by showing information is measurable — the bit. Everything since (channels, compression, error correction, digital computing) follows from the bit as primitive.

The predication algebra gives computation a different mathematical foundation by starting before the bit. The bit assumes you've already decided: true or false. The bilattice doesn't assume that. It starts from directed relation and gets four values — ⊥ (no relation witnessed), t (affirmed), f (denied), ⊤ (both, which is MORE information than either, not error). t and f — Shannon's bit — are what you get after eliminating the other two. Binary computing is what predication computing looks like after that elimination.

## The separation theorem parallel

Shannon's separation theorem: you can separate reliable communication into source coding (compression) and channel coding (error correction) and optimize them independently. This separation made telecommunications possible — you don't design a phone network end-to-end, you compress then protect, independently.

The adjunction ⊙ ⊣ ⇒ is a separation theorem for knowledge. ⊙ (extending) handles what information IS THERE — what models jointly entail when they compose. ⇒ (restricting) handles what information SURVIVES SCRUTINY — what one model concludes about another. The adjunction guarantees they compose correctly. You can extend and then restrict, or vice versa, consistently. This separates "what do we know?" from "what can we justify?" — and lets you optimize them independently.

Communication is a special case: a sender model and a receiver model composing. Shannon's channel is the fiber between them. Predication handles the general case: any models composing, not just sender-receiver pairs.

## The noise insight

In Shannon, noise corrupts signal. You spend channel capacity fighting it. In predication, what binary systems call noise — contradictions, incomplete data, conflicting sources — is ⊤ or ⊥. These are HIGHER in the knowledge ordering than clean t/f. They carry more information. The contradiction tells you the sources disagree. The unknown tells you nobody has spoken. Binary systems discard this as error. Predication systems compute with it.

## What settlement IS

Not "reaching fixpoint on a graph." Models receiving messages from each other, composing via ⊙, restricting via ⇒, propagating changes to connected models, until the system is self-consistent. This is computation. It converges (Proposition 8: ≤2 steps per predicate). It doesn't require halting, decidability, or Turing machines. It requires directed relations and the algebra.

The modal geometry of ANY set of directed relations — files on a disk, rows in a database, observations in a sensor network, claims in a governance document — is a predication computer. The algebra makes what it computes visible. FARS is one instantiation. The paper is about the principle, not the instantiation.
