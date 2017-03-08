# ggjanus
Personal package with extra ggplot themes


## Theme overview

- `theme_nice` : nice and blog-ready theme
- `theme_placeholder` : more themes to come...

## Install

```r
devtools::install_github("janusvm/ggjanus")
```

## Examples

```r
library("ggplot2")
library("ggjanus")

p <- ggplot(mtcars, aes(x = wt, y = mpg)) +
  geom_point(aes(color = factor(cyl))) +
  theme_nice()
```
