# Intersections with Sibling Works

This note maps how `The Method of Artificial Systems` should align with the author's other monograph-scale work in the sibling folders:

- `../symbolic-logic`
- `../behavior-hybrid-substrate`
- `../aibo-rcode`

The goal is not to collapse these projects into one another. The goal is to make their continuity legible, avoid duplicated claims, and give each work a distinct role inside a shared research program.

## Working position

`The Method of Artificial Systems` should be treated as the broadest conceptual and methodological statement in the set.

It is the place where the author defines:

- what an artificial system is
- why embodied machine life should not be reduced to narrow AI imitation
- why context, orchestration, choice, and autonomy belong together
- why experiments in robotics and machine embodiment matter

The sibling works then become supporting or specialized continuations of that framework rather than parallel reinventions of it.

## 1. Intersection with `symbolic-logic`

### What `symbolic-logic` is doing

The strongest thread in `../symbolic-logic` is not merely formal logic history. It is building a lineage:

- `Boole -> Venn -> Shannon -> Berkeley`

and then connecting Berkeley forward to embodied machine intelligence.

The note `BERKELEY-EMBODIED-MACHINE-INTELLIGENCE.md` is especially important because it argues that Berkeley should be read not only as a symbolic logician but as an early thinker of:

- physically realized intelligence
- input/output/control organization
- sensing and acting devices
- states and events
- robot behavior over time

### Why this matters here

This is highly compatible with `The Method of Artificial Systems`.

`The Method of Artificial Systems` argues for machine life as situated, organized, and behaviorally real. The Berkeley note offers a historical lineage showing that this view is not an arbitrary break from prior work. It helps show that embodied machine intelligence has deeper roots than mainstream AI summaries usually allow.

### Best alignment

This manuscript should treat `symbolic-logic` as part of its historical and conceptual support layer.

Suggested relationship:

- `The Method of Artificial Systems` states the method and the design philosophy.
- `symbolic-logic` supplies part of the intellectual prehistory and legitimacy of embodied machine organization.

### Boundary to keep clear

This manuscript should not become a long Berkeley paper.

It should borrow only enough from that line to establish:

- embodied machine intelligence has a real conceptual lineage
- logic and machinery were historically linked through organization and control, not only abstract deduction

The detailed Berkeley analysis belongs in `symbolic-logic`.

## 2. Intersection with `behavior-hybrid-substrate`

### What `behavior-hybrid-substrate` is doing

The notes in `../behavior-hybrid-substrate` position a third paper as an implementation-oriented architecture paper. The core emphasis is:

- behavior diagrams as executable control structure
- reactive and supervisory decomposition
- distributed realization across hybrid hardware/software substrate
- SOFTSIM as functional validation
- Apeiron / GA144 as embodied distributed realization

Its current framing already depends on the Berkeley-Heiserman continuity and on a layered architecture of:

- sensing
- state or memory
- control
- action
- recovery
- adaptation

### Why this matters here

This is a downstream engineering instantiation of the artificial-systems argument.

Where `The Method of Artificial Systems` speaks in terms such as orchestration, feature formation, and bounded choice, `behavior-hybrid-substrate` is trying to prove that a behavior architecture can actually be mapped onto an executable substrate.

### Best alignment

This manuscript should treat `behavior-hybrid-substrate` as an implementation descendant.

Suggested relationship:

- `The Method of Artificial Systems` defines the design ontology and methodological reasons for building embodied synthetic entities this way.
- `behavior-hybrid-substrate` tests whether that ontology can become executable architecture on a distributed technical substrate.

### Boundary to keep clear

This manuscript should not overclaim the engineering results of the substrate work.

It can point toward distributed control, layered behavior, and orchestration, but the proof burden for:

- node allocation
- cadence separation
- behavioral handoff
- simulation role
- hardware advantage

belongs to `behavior-hybrid-substrate`.

## 3. Intersection with `aibo-rcode`

### What `aibo-rcode` appears to be doing

The top-level README is brief, but the sibling notes in `symbolic-logic/AIBO-SECTION-NOTE.md` clarify the likely role: the AIBO work is a concrete behavioral-code paper where readers can see embodied control patterns at script level.

The important idea there is pedagogical as much as technical:

- begin with simpler monitored action
- move through intermediate cases
- only then reach richer mode structures such as `Football`

That note stresses the value of a graded behavioral vocabulary.

### Why this matters here

This is a practical demonstration layer for the method.

If `The Method of Artificial Systems` argues that machine life depends on organized behavior, situated action, and bounded choice, the AIBO code work can show those claims in actual robotic behavior scripts.

### Best alignment

This manuscript should treat the AIBO work as an example-rich embodiment track.

Suggested relationship:

- `The Method of Artificial Systems` provides the big vocabulary.
- `aibo-rcode` shows what parts of that vocabulary look like in executable embodied behavior.

### Boundary to keep clear

This manuscript should not depend on readers knowing AIBO internals.

AIBO should appear as a supporting example of embodied control, not as the sole or necessary proof of the whole method.

## Common vocabulary across the sibling works

The same cluster of ideas is already appearing across folders, sometimes under slightly different names.

The most reusable shared vocabulary looks like this:

- system
- environment
- embodiment
- sensing
- action
- state
- control
- orchestration
- behavior
- choice
- autonomy
- adaptation

This is promising because it means the projects can be made to reinforce one another with only light editorial normalization.

## A possible division of labor across the works

One clean way to position the overall program is:

- `The Method of Artificial Systems`:
  foundational statement of method, ontology, and design philosophy for artificial life
- `symbolic-logic`:
  historical and conceptual lineage from symbolic logic into embodied machine organization
- `behavior-hybrid-substrate`:
  executable architecture and distributed-substrate implementation argument
- `aibo-rcode`:
  behavioral-code case studies showing embodied control patterns in practice

This division gives each work a job.

## Recommended editorial use inside this manuscript

When revising `The Method of Artificial Systems`, the sibling works should inform the manuscript in these ways:

1. Use `symbolic-logic` to strengthen the historical chapter or background framing.
2. Use `behavior-hybrid-substrate` to sharpen claims about orchestration, layered control, and embodiment as engineering practice.
3. Use `aibo-rcode` to anchor abstract claims in concrete robotic behavior examples.

## What should change in the manuscript because of this

### The introduction should signal the larger program

The opening should make clear that this work is not a detached philosophical critique. It is the conceptual center of a broader embodied-machine research program that includes:

- historical reconstruction
- robotic behavior examples
- substrate and architecture experiments

### The historical critique should become more selective

Because `symbolic-logic` carries a more focused historical burden, this manuscript can be more disciplined in its use of history. It does not need to prove every historical point itself.

### The experimental dimension should become more explicit

Because the sibling works show actual implementation and behavioral directions, this manuscript can present embodiment and experiment earlier and more confidently.

### The terminology should be normalized

If the set of projects is going to read as one program, the key terms need to stabilize across them. In particular:

- `orchestration`
- `choice`
- `behavior`
- `control`
- `autonomy`
- `adaptation`

should not drift in meaning from repo to repo without notice.

## Short positioning statement

If one sentence is needed to align the projects, use something close to this:

`The Method of Artificial Systems` is the conceptual anchor of a broader body of work in which the history, code, and substrate of embodied machine intelligence are treated as parts of one constructive artificial-life program.

## Recommended next steps

1. Revise the top-level README of this repo so it explicitly mentions the relation to the sibling works.
2. Add a short prefatory note in the manuscript acknowledging the larger research program.
3. Use `symbolic-logic` selectively when rebuilding the historical framing.
4. Use `aibo-rcode` and `behavior-hybrid-substrate` selectively when rebuilding the embodiment and experiment sections.
