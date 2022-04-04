options(
  repos = c(CRAN = "https://cran.rstudio.com/",
            RSPM = "https://packagemanager.rstudio.com/all/latest",
            INLA = "https://inla.r-inla-download.org/R/testing"),

  renv.config.auto.snapshot = TRUE, ## Attempt to keep renv.lock updated automatically
  renv.config.rspm.enabled = TRUE, ## Use RStudio Package manager for pre-built package binaries
  renv.config.install.shortcuts = TRUE, ## Use the existing local library to fetch copies of packages for renv
  renv.config.cache.enabled = TRUE,   ## Use the renv build cache to speed up install times
  renv.config.cache.symlinks = TRUE  ## Keep full copies of packages locally than symlinks to make the project portable in/out of containers
)
source("renv/activate.R")
