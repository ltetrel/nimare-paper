# Package Organization

At present, the package is organized into 14 distinct modules.
`nimare.dataset` defines the `Dataset` class.
`nimare.meta` includes `Estimators` for coordinate- and image-based meta-analysis methods.
`nimare.results` defines the `MetaResult` class, which stores statistical maps produced by meta-analyses.
`nimare.correct` implements `Corrector` classes for family-wise error (FWE) and false discovery rate (FDR) multiple comparisons correction.
`nimare.annotate` implements a range of automated annotation methods, including latent Dirichlet allocation (LDA) and generalized correspondence latent Dirichlet allocation (GCLDA).
`nimare.decode` implements a number of meta-analytic functional decoding and encoding algorithms.
`nimare.io` provides functions for converting alternative meta-analytic dataset structure, such as Sleuth text files or Neurosynth datasets, to NiMARE format.
`nimare.transforms` implements a range of spatial and data type transformations, including a function to generate new images in the `Dataset` from existing image types.
`nimare.extract` provides methods for fetching datasets and models across the internet.
`nimare.generate` includes functions for generating data for internal testing and validation.
`nimare.base` defines a number of base classes used throughout the rest of the package.
Finally, `nimare.stats` and `nimare.utils` are modules for statistical and generic utility functions, respectively.
These modules are summarized in **Table 1**.