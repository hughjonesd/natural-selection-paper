This repository contains code to reproduce Hugh-Jones and Abdellaoui (2020)
"Natural Selection in Contemporary Humans is Linked to Income and Substitution Effects".

It doesn't contain the complete history of our original (private) repository. This
has some copies of copyright papers. If you'd like to look at our commit
history, contact davidhughjones@gmail.com.

The code creates a pdf from the Rmarkdown file "why-natural-selection.Rmd".
If you just want the pdf, it's [available from REPEC](https://ideas.repec.org/p/uea/ueaeco/2021-02.html).

# To run

Ensure you have a recent R, and install the `drake` library from CRAN.

Clone the repository (or download it as a tarball).

Edit directory locations in `_drake.R`.

Within R:

```r
source("_drake.R")
drake::r_make()
```

You may need to install additional R libraries.
