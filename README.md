### Build

Install requirements in R:

```
install.packages("postcards")
```

To compile index.Rmd to index.html:

```
library(postcards)
library(rmarkdown)

render("index.Rmd")
```
