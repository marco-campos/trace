# TRACE

**T**opological **R**epresentation **a**nd **A**nalysis of **C**loud **E**volution

TRACE is a Python package for applying topological data analysis (TDA) to *temporally evolving point clouds*. It provides:

- Temporal persistence signatures
- Zigzag persistence for time-varying data
- Feature trajectories from evolving homological structures
- Vectorized descriptors for downstream ML

## Features (planned)

- [ ] Sliding-window persistent homology
- [ ] Cubical & simplicial filtrations over time
- [ ] Topological signatures as features
- [ ] Support for `.npy` or `.h5` time-series point cloud datasets

## Installation

TBD — once pushed to PyPI.

## Usage

```python
from trace import core
core.compute_signature(time_series_data)

