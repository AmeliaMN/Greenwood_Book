You need at least R 4.4.0 to compile this book (dependency for `coneproj`). You also need a number of R packages.   

From CRAN:

```
install.packages(c("bookdown", "tidyverse", "pander", "gridExtra", "mosaic", "yarrr", "car", "MASS", "GGally", "psych", "beanplot", "heplots", "effects", "gplots", "multcomp", "faraway", "vcd", "poLCA", "tigerstats", "alr4", "spuRs", "smdata", "MuMIn", "coneproj", "corrplot", "viridis", "openintro", "ggthemes", "ggstance"))

install.packages("devtools") # to install from GitHub
```

From GitHub:

```
devtools::install_github("edwindj/ffbase", subdir="pkg")
devtools::install_github("mtennekes/tabplot")
```

I also needed an upgraded version of LaTeX, which I got from tinytex:

```
tinytex::reinstall_tinytex(repository = "illinois")
```

and some additional LaTeX packages that for whatever reason my system wouldn't install automatically

```
tlmgr_install("tocbibind")
tlmgr_install("cancel")
tlmgr_install("truncate")
tlmgr_install("sistyle")
```

