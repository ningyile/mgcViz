
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/mgcViz)](https://cran.r-project.org/package=mgcViz)
[![Build Status](https://travis-ci.org/mfasiolo/mgcViz.svg?branch=master)](https://travis-ci.org/mfasiolo/mgcViz)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/mfasiolo/mgcViz?branch=master&svg=true)](https://ci.appveyor.com/project/mfasiolo/mgcViz)

# **mgcViz**: visual tools for Generalized Additive Models

The `mgcViz` R package offers visual tools for Generalized Additive Models (GAMs). The visualizations provided by `mgcViz` differs from those implemented in `mgcv`, in that most of the plots are based on `ggplot2`'s powerful layering system. This has been implemented by wrapping several `ggplot2` layers and integrating them with computations specific to GAM models. Further, `mgcViz` uses binning and/or sub-sampling to produce plots that can scale to large datasets (n = O(10^7)), and offers a variety of new methods for visual model checking/selection.

See the [vignette](https://mfasiolo.github.io/mgcViz/articles/mgcviz.html) for an introduction to the following categories of visualizations: 

1. **smooth and parametric effect plots**: layered plots based on `ggplot2` and interactive 3d visualizations based on the `rgl` library;   

2. **model checks**: interactive QQ-plots, traditional residuals plots and layered residuals checks along one or two covariates;

3. **special plots**: differences-between-smooths plots in 1 or 2D and plotting multiple slices of multidimensional smooth effects.

# How to linstall
```R
install.packages("devtools")
devtools::install_github('ningyile/mgcViz')
```

# Features
添加3d数据，方便之后在[rgl package](https://github.com/dmurdoch/rgl)(推荐优先使用`rgl`包)或[plotly包](https://github.com/plotly/plotly.R)中绘制个性化3d图形

Ehanced 3D data output so that you can create customized 3D Surface plots with the [rgl package](https://github.com/dmurdoch/rgl)(recommend) or [plotly  package](https://github.com/plotly/plotly.R) later.
