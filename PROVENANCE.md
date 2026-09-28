# Source provenance

This `interactive-nav/sim` branch is part of the public fork
[`piqiuni/molmospaces-interactive-nav`](https://github.com/piqiuni/molmospaces-interactive-nav)
of [Allen Institute for AI's MolmoSpaces](https://github.com/allenai/molmospaces).
It descends from upstream commit `1320b266d2b47aaa81c5f7a419cb9d3474e6994d`
and contains the reviewed simulator commits through
`4fae4842eecebc02527126e1f3f67e852b451962` from the former
`piqiuni/molmospaces` fork.

The simulator code also appeared as an independent source snapshot in
[`piqiuni/molmospaces-interactive-nav-sim`](https://github.com/piqiuni/molmospaces-interactive-nav-sim)
at commit `257a33de7d523d2672698941c9f6efd7bdff931e`. This branch keeps
the upstream and simulator Git ancestry while applying that snapshot's
manual-only workflow triggers and public documentation. The original
license and copyright notices remain in the source tree.

This branch excludes the private navigation and semantic decision
implementation. The fork's `main` branch is reserved for upstream updates;
review changes before merging them into this simulator branch, and never
merge private algorithm history into the public fork. The public benchmark
policy interface is described in the
[evaluation protocol](scripts/InteractiveNav/evaluation/evaluation_protocol.md).
