---
icon: fas fa-microscope
order: 1
math: true
---

## Quantum Error Correction

WIP



## Classical Simulation of Boson Sampling

Boson Sampling is a quantum optical experiment, and a non-universal model of computation, where we send indistinguishable individual photons[^1] into a linear optical interferometer on many modes, and measure how many come out in each mode. This is considered as a candidate for demonstrating quantum advantage because obtaining these samples classically, without a quantum system, is generally hard. The reason is that the simulation requires computing matrix permanents, which is a #P-hard problem in the general case.

However, in certain architectures (such as shallow or loop-based circuits, see below), one can exploit the structure to speed up the classical simulation. These structured setups are usually easier to build experimentally, but the easier classical simulation means they may provide no advantage. The challenge is identifying the boundary between these regimes: how simple or structured can a system be such that it is still complex to simulate?

[^1]: More generally, one may use other quantum states of light, like Gaussian states, etc.
