# Contribution (Poster) for the Metabolomics 2020 Conference

This repository contains the contribution to the (online) conference
[metabolomics2020](http://metabolomics2020.org/) of the metabolomics society.

## Title

A scalable and flexible infrastructure for mass spectrometry data in R

## Authors

Johannes Rainer, Sebastian Gibb, Laurent Gatto.


## Abstract

The R statistical environment has become one of the most frequently used
analysis platforms in (bio)statistical data analysis. Several software solutions
exist also in R to handle, process and analyze metabolomics data or mass
spectrometry (MS) data in general, but they mostly don't share data structures
hence preventing interoperability.

The objective of the R for Mass Spectrometry initiative is to provide a data
analysis and development environment that is flexible (it must support
user-centered applications such as data exploration and analysis, and
developer-centered requirements such as enabling novel method development),
efficient and scalable (applicable to small and large data sets on desktops,
laptops or HPC systems), reproducible (to support reproducible research
practices) and thoroughly tested and documented.

As first packages we implemented the `MsCoreUtils` package that provides core
functionality for MS data which is independent of any data structure, and the
`Spectra` package to represent MS spectra data independently of its storage or
origin and provide user functionality to visualize and process this data
efficiently, including centroiding, smoothing, combining, normalizing, comparing
and matching of MS spectra e.g. against MS spectral databases. Adapting existing
software packages such as `xcms` to these new infrastructure will simplify their
integration into complete data analysis pipelines.

The R for Mass Spectrometry initiative has a strong commitment to open source
software and community contributions are highly welcome. All of its packages
are, or will be, part of the Bioconductor project.
