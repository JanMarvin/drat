# Drat Repo for JanMarvin

Since I neither have enough time nor am I willing enough to bother with CRAN for
my builds, I am providing ziped sources and binaries for Windows of my 
R-packages in this drat repo.

You can include it using

```{R}
drat::addRepo("JanMarvin")
```

Afterwards you can install simply using `install.packages()`.

Currently it contains [`nlsur`](https://github.com/JanMarvin/nlsur), 
[`readspss`](https://github.com/JanMarvin/readspss) and
[`readstata13`](https://github.com/sjewo/readstata13).


## R-packages in this repo

### [nlsur](https://github.com/JanMarvin/nlsur)

R-package for nonlinear seemingly unrelated estimation. This allows estimation
of demand systems in R (like the famous almost ideal demand system).

### [readspss](https://github.com/JanMarvin/readspss)

R-package to import/export SPSS sav, zsav and por files to and from R. The
package is written from scratch using code snippets from different other 
sources PSPP, TDA and foreign. The package should import every por, zsav and
sav file out there in the wild.

### [readstata13](https://github.com/sjewo/readstata13)

R-package to import/export Stata dta files to and from R. The package source
code is located at [sjewo/readstata13](https://github.com/sjewo/readstata13).

## Binary builds

Packages are known to build on MacOS too, but I do not own a Mac and since have
no way to provide Mac binaries.
