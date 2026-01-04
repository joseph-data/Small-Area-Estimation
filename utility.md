
# ´pak´ by posit

begin with these 

´´´{r}
renv::settings$use.pak(TRUE)

´´´

[Documentation](https://pak.r-lib.org/)

´´´{r}
install.packages("pak")


pak::pkg_install(c(
  "tidyverse",
  "data.table",
  "fixest",
  "emdi",
  "sf",
  "targets"
))


´´´