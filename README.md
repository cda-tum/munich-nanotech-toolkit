<p align="center">
  <a href="https://www.cda.cit.tum.de/research/nanotech/mnt/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cda-tum/fiction/main/docs/_static/mnt_light.svg">
      <img width="60%" src="https://raw.githubusercontent.com/cda-tum/fiction/main/docs/_static/mnt_dark.svg" alt="Munich Nanotech Toolkit logo">
    </picture>
  </a>
</p>

# Munich Nanotech Toolkit

The Munich Nanotech Toolkit (MNT) is a collection of open-source design automation tools for field-coupled
nanocomputing (FCN) from the Chair for Design Automation at the Technical University of Munich. The tools cover
logic synthesis, placement and routing, layout verification, technology mapping, and physical simulation.
Supported technologies include quantum-dot cellular automata (QCA), in-plane nanomagnet logic (iNML), and silicon
dangling bonds (SiDBs).

[MNT at TUM](https://www.cda.cit.tum.de/research/nanotech/mnt/) ·
[*fiction* documentation](https://fiction.readthedocs.io/) ·
[MNT flyer (PDF)](https://www.cda.cit.tum.de/flyers/mnt_flyer.pdf)

## Tools

- [*fiction*](https://github.com/cda-tum/fiction) — C++ library, Python bindings, and command-line interface for logic synthesis, physical design, verification, and SiDB simulation. [Documentation](https://fiction.readthedocs.io/)
- [MNT Designer](https://github.com/cda-tum/mnt-designer) — Graphical workspace for creating, editing, checking, and exporting FCN circuit layouts. [Usage](https://github.com/cda-tum/mnt-designer#usage-of-mnt-designer)
- [MNT NanoPlaceR](https://github.com/cda-tum/mnt-nanoplacer) — Reinforcement learning for gate placement with routing during placement. [Usage](https://github.com/cda-tum/mnt-nanoplacer#usage)
- [MNT Bench](https://github.com/cda-tum/mnt-bench) — Benchmark circuits and layouts for comparing FCN design methods. [Benchmark explorer](https://www.cda.cit.tum.de/mntbench/) · [Documentation](https://www.cda.cit.tum.de/mntbench/description)
- [Operational Domain Explorer](https://github.com/cda-tum/mnt-opdom-explorer) — Graphical tool for exploring the physical parameters under which SiDB gates operate correctly. [Documentation](https://github.com/cda-tum/mnt-opdom-explorer#readme)
- [Plugins for SiQAD](https://github.com/cda-tum/mnt-siqad-plugins) — ClusterComplete, QuickExact, and QuickSim simulation engines for the SiQAD graphical environment. [Quick start](https://github.com/cda-tum/mnt-siqad-plugins#quick-start)
- [Bestagon Gate Library](https://github.com/cda-tum/mnt-bestagon-library) — Hexagonal gate layouts and simulation files for SiDB logic. [Gate library files](https://github.com/cda-tum/mnt-bestagon-library#readme)

## Book

[*Design Automation for Field-coupled Nanotechnologies*](https://link.springer.com/book/10.1007/978-3-030-89952-3)
covers physical design, clocking, and formal verification for FCN and introduces the *fiction* framework.
Marcel Walter, Robert Wille, Frank Sill Torres, and Rolf Drechsler. Springer, 2022.

## Cite MNT

If you use the toolkit in your research, cite the
[MNT paper](https://doi.org/10.1109/NANO61778.2024.10628747).

```bibtex
@inproceedings{mnt,
  author    = {Walter, Marcel and Drewniok, Jan and Hofmann, Simon and Hien, Benjamin and Wille, Robert},
  title     = {The Munich Nanotech Toolkit ({MNT})},
  booktitle = {2024 IEEE 24th International Conference on Nanotechnology (NANO)},
  pages     = {454--459},
  year      = {2024},
  doi       = {10.1109/NANO61778.2024.10628747}
}
```

## GitHub information

| Repository | Issue tracker | Latest release | Forks | Stars |
| --- | --- | ---: | ---: | ---: |
| [`fiction`](https://github.com/cda-tum/fiction) | [Issues](https://github.com/cda-tum/fiction/issues) | [![Latest release][badge-fiction-release]](https://github.com/cda-tum/fiction/releases/latest) | [![Forks][badge-fiction-forks]](https://github.com/cda-tum/fiction/forks) | [![Stars][badge-fiction-stars]](https://github.com/cda-tum/fiction) |
| [`mnt-designer`](https://github.com/cda-tum/mnt-designer) | [Issues](https://github.com/cda-tum/mnt-designer/issues) | [![Latest release][badge-mnt-designer-release]](https://github.com/cda-tum/mnt-designer/releases/latest) | [![Forks][badge-mnt-designer-forks]](https://github.com/cda-tum/mnt-designer/forks) | [![Stars][badge-mnt-designer-stars]](https://github.com/cda-tum/mnt-designer) |
| [`mnt-nanoplacer`](https://github.com/cda-tum/mnt-nanoplacer) | [Issues](https://github.com/cda-tum/mnt-nanoplacer/issues) | [![Latest release][badge-mnt-nanoplacer-release]](https://github.com/cda-tum/mnt-nanoplacer/releases/latest) | [![Forks][badge-mnt-nanoplacer-forks]](https://github.com/cda-tum/mnt-nanoplacer/forks) | [![Stars][badge-mnt-nanoplacer-stars]](https://github.com/cda-tum/mnt-nanoplacer) |
| [`mnt-bench`](https://github.com/cda-tum/mnt-bench) | [Issues](https://github.com/cda-tum/mnt-bench/issues) | [![Latest release][badge-mnt-bench-release]](https://github.com/cda-tum/mnt-bench/releases/latest) | [![Forks][badge-mnt-bench-forks]](https://github.com/cda-tum/mnt-bench/forks) | [![Stars][badge-mnt-bench-stars]](https://github.com/cda-tum/mnt-bench) |
| [`mnt-opdom-explorer`](https://github.com/cda-tum/mnt-opdom-explorer) | [Issues](https://github.com/cda-tum/mnt-opdom-explorer/issues) | — | [![Forks][badge-mnt-opdom-explorer-forks]](https://github.com/cda-tum/mnt-opdom-explorer/forks) | [![Stars][badge-mnt-opdom-explorer-stars]](https://github.com/cda-tum/mnt-opdom-explorer) |
| [`mnt-siqad-plugins`](https://github.com/cda-tum/mnt-siqad-plugins) | [Issues](https://github.com/cda-tum/mnt-siqad-plugins/issues) | [![Latest release][badge-mnt-siqad-plugins-release]](https://github.com/cda-tum/mnt-siqad-plugins/releases/latest) | [![Forks][badge-mnt-siqad-plugins-forks]](https://github.com/cda-tum/mnt-siqad-plugins/forks) | [![Stars][badge-mnt-siqad-plugins-stars]](https://github.com/cda-tum/mnt-siqad-plugins) |
| [`mnt-bestagon-library`](https://github.com/cda-tum/mnt-bestagon-library) | [Issues](https://github.com/cda-tum/mnt-bestagon-library/issues) | — | [![Forks][badge-mnt-bestagon-library-forks]](https://github.com/cda-tum/mnt-bestagon-library/forks) | [![Stars][badge-mnt-bestagon-library-stars]](https://github.com/cda-tum/mnt-bestagon-library) |

## PyPI downloads

| Package | Latest version | Weekly | Monthly | Total |
| --- | ---: | ---: | ---: | ---: |
| [`mnt.pyfiction`](https://pypi.org/project/mnt-pyfiction/) | [![PyPI version][badge-mnt-pyfiction-pypi]](https://pypi.org/project/mnt-pyfiction/) | [![Weekly downloads][badge-mnt-pyfiction-weekly]](https://pypistats.org/packages/mnt-pyfiction) | [![Monthly downloads][badge-mnt-pyfiction-monthly]](https://pypistats.org/packages/mnt-pyfiction) | [![Total downloads][badge-mnt-pyfiction-total]](https://pepy.tech/projects/mnt-pyfiction) |
| [`mnt.bench`](https://pypi.org/project/mnt-bench/) | [![PyPI version][badge-mnt-bench-pypi]](https://pypi.org/project/mnt-bench/) | [![Weekly downloads][badge-mnt-bench-weekly]](https://pypistats.org/packages/mnt-bench) | [![Monthly downloads][badge-mnt-bench-monthly]](https://pypistats.org/packages/mnt-bench) | [![Total downloads][badge-mnt-bench-total]](https://pepy.tech/projects/mnt-bench) |
| [`mnt.nanoplacer`](https://pypi.org/project/mnt-nanoplacer/) | [![PyPI version][badge-mnt-nanoplacer-pypi]](https://pypi.org/project/mnt-nanoplacer/) | [![Weekly downloads][badge-mnt-nanoplacer-weekly]](https://pypistats.org/packages/mnt-nanoplacer) | [![Monthly downloads][badge-mnt-nanoplacer-monthly]](https://pypistats.org/packages/mnt-nanoplacer) | [![Total downloads][badge-mnt-nanoplacer-total]](https://pepy.tech/projects/mnt-nanoplacer) |

## Acknowledgements

The [Chair for Design Automation](https://www.cda.cit.tum.de/) at the
[Technical University of Munich](https://www.tum.de/en/) develops the Munich Nanotech Toolkit.
The Bavarian State Ministry for Science and Arts has supported MNT through the Distinguished Professorship Program.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/munich-quantum-toolkit/.github/refs/heads/main/docs/_static/logo-tum-dark.svg">
    <img width="28%" src="https://raw.githubusercontent.com/munich-quantum-toolkit/.github/refs/heads/main/docs/_static/logo-tum-light.svg" alt="Technical University of Munich logo">
  </picture>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img width="16%" src="https://raw.githubusercontent.com/munich-quantum-toolkit/.github/refs/heads/main/docs/_static/logo-bavaria.svg" alt="Bavarian coat of arms">
</p>

[badge-fiction-release]: https://img.shields.io/github/v/release/cda-tum/fiction?style=flat-square&label=
[badge-fiction-forks]: https://img.shields.io/github/forks/cda-tum/fiction?style=flat-square&label=
[badge-fiction-stars]: https://img.shields.io/github/stars/cda-tum/fiction?style=flat-square&label=
[badge-mnt-designer-release]: https://img.shields.io/github/v/release/cda-tum/mnt-designer?style=flat-square&label=
[badge-mnt-designer-forks]: https://img.shields.io/github/forks/cda-tum/mnt-designer?style=flat-square&label=
[badge-mnt-designer-stars]: https://img.shields.io/github/stars/cda-tum/mnt-designer?style=flat-square&label=
[badge-mnt-nanoplacer-release]: https://img.shields.io/github/v/release/cda-tum/mnt-nanoplacer?style=flat-square&label=
[badge-mnt-nanoplacer-forks]: https://img.shields.io/github/forks/cda-tum/mnt-nanoplacer?style=flat-square&label=
[badge-mnt-nanoplacer-stars]: https://img.shields.io/github/stars/cda-tum/mnt-nanoplacer?style=flat-square&label=
[badge-mnt-bench-release]: https://img.shields.io/github/v/release/cda-tum/mnt-bench?style=flat-square&label=
[badge-mnt-bench-forks]: https://img.shields.io/github/forks/cda-tum/mnt-bench?style=flat-square&label=
[badge-mnt-bench-stars]: https://img.shields.io/github/stars/cda-tum/mnt-bench?style=flat-square&label=
[badge-mnt-opdom-explorer-forks]: https://img.shields.io/github/forks/cda-tum/mnt-opdom-explorer?style=flat-square&label=
[badge-mnt-opdom-explorer-stars]: https://img.shields.io/github/stars/cda-tum/mnt-opdom-explorer?style=flat-square&label=
[badge-mnt-siqad-plugins-release]: https://img.shields.io/github/v/release/cda-tum/mnt-siqad-plugins?style=flat-square&label=
[badge-mnt-siqad-plugins-forks]: https://img.shields.io/github/forks/cda-tum/mnt-siqad-plugins?style=flat-square&label=
[badge-mnt-siqad-plugins-stars]: https://img.shields.io/github/stars/cda-tum/mnt-siqad-plugins?style=flat-square&label=
[badge-mnt-bestagon-library-forks]: https://img.shields.io/github/forks/cda-tum/mnt-bestagon-library?style=flat-square&label=
[badge-mnt-bestagon-library-stars]: https://img.shields.io/github/stars/cda-tum/mnt-bestagon-library?style=flat-square&label=
[badge-mnt-pyfiction-pypi]: https://img.shields.io/pypi/v/mnt-pyfiction?style=flat-square&label=
[badge-mnt-pyfiction-weekly]: https://img.shields.io/pypi/dw/mnt-pyfiction?style=flat-square&label=
[badge-mnt-pyfiction-monthly]: https://img.shields.io/pypi/dm/mnt-pyfiction?style=flat-square&label=
[badge-mnt-pyfiction-total]: https://img.shields.io/pepy/dt/mnt-pyfiction?style=flat-square&label=
[badge-mnt-bench-pypi]: https://img.shields.io/pypi/v/mnt-bench?style=flat-square&label=
[badge-mnt-bench-weekly]: https://img.shields.io/pypi/dw/mnt-bench?style=flat-square&label=
[badge-mnt-bench-monthly]: https://img.shields.io/pypi/dm/mnt-bench?style=flat-square&label=
[badge-mnt-bench-total]: https://img.shields.io/pepy/dt/mnt-bench?style=flat-square&label=
[badge-mnt-nanoplacer-pypi]: https://img.shields.io/pypi/v/mnt-nanoplacer?style=flat-square&label=
[badge-mnt-nanoplacer-weekly]: https://img.shields.io/pypi/dw/mnt-nanoplacer?style=flat-square&label=
[badge-mnt-nanoplacer-monthly]: https://img.shields.io/pypi/dm/mnt-nanoplacer?style=flat-square&label=
[badge-mnt-nanoplacer-total]: https://img.shields.io/pepy/dt/mnt-nanoplacer?style=flat-square&label=
