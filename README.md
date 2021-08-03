# CORAL

Trying to get http://phanstiel-lab.med.unc.edu/CORAL/ to work locally or as a PamApp in BioNavigator.
Forked from https://github.com/dphansti/CORAL.

**Goals:**

- Allow input .txt from UKA without additional column selection<sup>1</sup> ✅
- Allow 2 .txts to be uploaded (e.g., for STK + PTK data)
- Package as PamApp to be used in BioNavigator

<sup>1</sup> Currently set to `Median.Kinase.Statistic` for branch and node color and `Median.Final.score` for node size.

# Installation
```
R < install.R --no-save
R < global.R --no-save
R -e "shiny::runApp('.')"
```
