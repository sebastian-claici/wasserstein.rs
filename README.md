# wasserstein.rs

Rust code for [Optimal Transport](https://en.wikipedia.org/wiki/Transportation_theory_(mathematics)) algorithms. The goal of this repo is to eventually cover all of the algorithms in Cuturi and Peyre's excellent survey [Computational Optimal Transport](https://arxiv.org/pdf/1803.00567), but I make no promises. Along the way, I also plan on implementing algorithms I worked on during my PhD in a clean and robust way.

## Roadmap

Rough roadmap:
- [ ] Hungarian assignment algorithm to compute transport maps
- [ ] Entropy regularized optimal transport for approximate solutions
- [ ] Barycenter problems and solvers
- [ ] Unbalanced optimal transport solvers
- [ ] Gromov-Wasserstein problems

## Why do we need this?

We don't. Most optimal transport researchers should be happy enough with [POT](https://pythonot.github.io/) which has significantly more contributors and a large user-base. This is more of a nostalgia project for me as I revisit the topics I worked on in academia. If it ends up being fast or useful to someone, so much the better.

## Are there plans for Python bindings?

Eventually.
