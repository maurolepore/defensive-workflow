---
title: "Asking for help"
subtitle: Fixing a problem by installing dev version of a package
author: "Your name"
date: "2018-04-08"
output:
  html_document:
    toc: yes
    toc_depth: '3'
    theme: united
    keep_md: true
---



## Exposing an error

```R
remove.packages("reprex")
```

* TODO: Restart (Shift + Control + F10)

```R
broken_reprex <- "https://cran.r-project.org/src/contrib/reprex_0.1.2.tar.gz"
install.packages(broken_reprex, repos = NULL, type = "source")
```

Try

* Copy to clipboard

```R
(y <- 1:4)
mean(y)
```

* Run

```R
reprex::reprex()
````

## Searching for help

![](https://i.imgur.com/RW0virM.png)

---

![](https://i.imgur.com/ZoZNs1f.png)

Solution

```R
devtools::install_github("tidyverse/reprex")
# Or
# remotes::install_github("tidyverse/reprex")
```

Retry

* Copy to clipboard

```R
(y <- 1:4)
mean(y)
```

* Run

```R
reprex::reprex()
````
