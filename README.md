# A quick hands-on tutorial into effectively using R with Rstudio and packages from the tidyverse

## Looking at the slides

To just look at the slides, just clone this repository...
```
git clone https://github.com/dlaehnemann/Tut_R_TidyData
```
...and open `Tut_R_TidyData.html` from the respective directory in any (contemporary) web browser.

## Changing the slides

### 1. Edit the Rmarkdown file `Tut_R_TidyData.Rmd`

Links for how to do this:
* [Main Rmarkdown documentation](http://rmarkdown.rstudio.com/)
* [Rmarkdown cheat sheet](https://www.rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf)
* [knitr (code engine behind Rmarkdown) with other languages](https://yihui.name/knitr/demo/engines/)
* [ioslides with Rmarkdown intro](http://rmarkdown.rstudio.com/ioslides_presentation_format.html)

### 2. Recompile `Tut_R_TidyData.html` using `R`:
```
install.packages("rmarkdown")
install.packages("knitr")
library("rmarkdown")
library("knitr")
render("Tut_R_TidyData.Rmd")
```
