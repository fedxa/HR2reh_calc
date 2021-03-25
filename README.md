# Some like it hot: R² heals Higgs inflation, but does not cool it

Code used in the https://arxiv.org/abs/1904.04737

All the plots are produced by `reheat_plots.ipynb`

## Prerequisites

To install julia -- follow the instructions on https://julialang.org/
Then start julia and run the following to install the required packages

```
import Pkg
Pkg.add(["IJulia", "DifferentialEquations", "Plots", "PyPlot", "SymEngine", "NBInclude"])
```

To use the Jupyter notebooks start the Julia and run

```
using IJulia
notebook()
```

First starts are _very_ slow, then when all is downloaded/precompiled it runs much faster.
