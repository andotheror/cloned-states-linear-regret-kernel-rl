# Cloned States, Linear Regret: A Representation-Invariant Theory of Kernel MDPs

## Abstract

A common kernel-MDP assumption requires every scalar transition slice $z\mapsto P_h(s'\mid z)$ to have bounded norm in a state-action RKHS. We show that this condition measures the names assigned to next states, not the decision problem. Replacing a state by $m$ behaviorally identical clones divides every associated slice norm by $m$, while preserving all policy values, every learning algorithm's attainable observation laws, minimax regret, and the kernel's maximum information gain. More strongly, we construct a fixed two-step MDP domain and a fixed Matern kernel with sublinear information gain for which the coordinatewise condition, with any prescribed constant, permits linear minimax regret. This gives a negative answer to the COLT 2024 no-regret open problem under its stated assumption. We then introduce the Bellman radius, the operator norm of the transition kernel from bounded values to the state-action RKHS. It is invariant to state cloning, is the exact constant needed for Bellman closure, and is equivalent up to a factor two to the semivariation of an RKHS-valued transition measure. An integrable RKHS norm of a transition density is a verifiable stronger condition. It exposes the missing state-volume factor in the frequently cited coordinatewise argument. These results separate valid Bellman-closure and conditional-embedding theorems from representation-dependent sufficient conditions, and give a drop-in premise for future kernel RL guarantees.

## Contributions

- We prove an exact state-refinement theorem. State cloning preserves the
 entire projected learning experiment, minimax regret, and maximum information
 gain, while coordinate transition norms decrease by arbitrary factors.
- We prove a linear minimax-regret lower bound under the stated assumption of. The state space, reward, and Matern kernel are fixed,
 and the kernel has $o(T)$ information gain.
- We characterize a representation-invariant replacement through the Bellman
 radius, semivariation, and transition-density variation. The hierarchy gives exact
 Bellman closure and clarifies when coordinate assumptions can be repaired.
- We audit the proof-level consequence across kernel-RL results from 2020 to
 2026. Direct Bellman-closure, smooth-Bellman, and bounded conditional-embedding
 results remain intact. Claims that derive closure from coordinate slices require a
 cardinality, volume, or operator-radius term.

## Keywords

kernel reinforcement learning, Markov decision processes, information gain, regret lower bounds, RKHS, representation invariance

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
