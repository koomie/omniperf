[![Docs](https://github.com/AMDResearch/omniperf/actions/workflows/pages/pages-build-deployment/badge.svg?branch=gh-pages)](https://amdresearch.github.io/omniperf/)
[![DOI](https://zenodo.org/badge/561919887.svg)](https://zenodo.org/badge/latestdoi/561919887)
[![GitHub commits since last release](https://img.shields.io/github/commits-since/AMDResearch/omniperf/latest/dev.svg)](https://github.com/AMDResearch/omniperf/compare/main...dev) 

# Omniperf

## General
Omniperf is a system performance profiling tool for machine
learning/HPC workloads running on AMD MI GPUs. The tool presently
targets usage on MI100 and MI200 accelerators.

* For more information on available features, installation steps, and
workload profiling and analysis, please refer to the online
[documentation](https://amdresearch.github.io/omniperf).

* Omniperf is an AMD open source research project and is not supported
as part of the ROCm software stack. We welcome contributions and
feedback from the community. Please see the
[CONTRIBUTING.md](CONTRIBUTING.md) file for additional details on our
contribution process.

* Licensing information can be found in the [LICENSE](LICENSE) file.

## Development 

Omniperf follows a
[main-dev](https://nvie.com/posts/a-successful-git-branching-model/)
branching model. As a result, our latest stable release is shipped
from the `main` branch, while new features are developed in our
`dev` branch.

Before publishing a new release, we'll open a new `release-*` branch
from `dev` with `*` being the version number of the upcoming
release. This branch will only receive bug fixes and users may
checkout to preview upcoming features.

## How to Cite

This software can be cited using a Zenodo
[DOI](https://doi.org/10.5281/zenodo.7314631) reference. A BibTex
style reference is provided below for convenience:

```
@software{xiamin_lu_2022_7434848,
  author       = {Xiaomin Lu and
                  Cole Ramos and
                  Fei Zheng and
                  Karl W. Schulz and
                  Jose Santos},
  title        = {AMDResearch/omniperf: v1.0.5 (13 December 2022)},
  month        = dec,
  year         = 2022,
  publisher    = {Zenodo},
  version      = {v1.0.5},
  doi          = {10.5281/zenodo.7314631},
  url          = {https://doi.org/10.5281/zenodo.7314631}
}
```

