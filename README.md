# Gauge-Invariant Time Perception

This repository contains the manuscript and supporting materials for:

**Gauge-Invariant Time Perception and the Minimal Conditions for Interior Sensitivity**  
Nathan Hangen

## Overview

This work studies whether a model of perceived time can be both invariant under reparameterization of physical time and sensitive to the internal structure of a temporal trajectory.

The central result is that memoryless gauge-invariant models collapse to endpoint-only functionals. If a model has no internal state and must remain invariant under smooth changes of time parameterization, then it cannot distinguish two paths that share the same endpoints.

The manuscript then shows that internal memory is necessary but not sufficient for interior sensitivity. Matched-endpoint path splitting requires a nontrivial intrinsic drive defined in tau-space.

## Main Claim

A gauge-invariant model of perceived time cannot obtain interior sensitivity from coordinate-time derivatives alone.

Instead:

- memoryless invariant models collapse to endpoint-only behavior
- constant-drive memory models remain endpoint-collapsed
- nontrivial tau-intrinsic drive is required for matched-endpoint path splitting
- coordinate-dependent observers fail gauge-consistency tests by orders of magnitude

## Key Definitions

A gauge-equivalent trajectory is related by a smooth, strictly increasing reparameterization of time:

```math
\tau_2(t)=\tau_1(\phi(t)), \qquad \phi(0)=0,\quad \phi(T)=T,\quad \phi'(t)>0
```

A gauge-invariant functional must be constant over this equivalence class.

The locked invariant readout is:

```math
\Delta P = k[m(\tau_T)-m(\tau_0)]
```

where $m(\tau)$ is an internal memory state evolving in intrinsic time.

## Repository Contents

```text
.
├── paper.pdf          # Manuscript PDF
├── paper.tex          # LaTeX source
├── references.bib     # Bibliography file
├── plots/             # Manuscript figures
├── sections/          # LaTeX subsections
├── README.md
└── LICENSE
```

## Planned Additions

```text
code/                  # Supporting or reproduction code
results/               # Experimental outputs and generated results
CITATION.cff           # Formal citation metadata
```

These materials will be added as the public research artifact is cleaned and organized.

## Experimental Summary

The manuscript compares invariant and coordinate-dependent model classes using matched-endpoint and warp-stress tests.

The invariant class remains stable under reparameterization. Coordinate-dependent observers show large gauge violations, with reported separation from the invariant baseline exceeding $10^{12}$ in the Family-B gauge comparison. The manuscript also reports that curvature-driven intrinsic models recover matched-endpoint splitting while preserving gauge consistency.

## Status

This is a working manuscript under revision.

The manuscript has not completed peer review. Figures, code, and supporting materials are being organized for public inspection and reproducibility.

## Citation

A formal citation file will be added after the manuscript metadata is finalized.

For now, cite as:

```bibtex
@misc{hangen2026gaugeinvarianttime,
  title        = {Gauge-Invariant Time Perception and the Minimal Conditions for Interior Sensitivity},
  author       = {Hangen, Nathan},
  year         = {2026},
  note         = {Working manuscript}
}
```

## License

This manuscript, figures, and documentation are licensed under the Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0).

Derivative works must be distributed under the same or a compatible license.

Code, if added later, may be licensed separately.
