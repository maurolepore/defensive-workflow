---
title: "Defensive workflow"
subtitle: Risk assessment, tools, and habits for better research
author: cc https://bit.ly/mauro_lepore | doc http://bit.ly/defensive-doc
output: 
  ioslides_presentation:
    keep_md: true
---





## What does is mean to be defensive? | <small> bit.ly/defensive-workflow </small>

<img src="http://bit.ly/2EucGrk" align="center" height=400 />



## What does is mean to be defensive? | <small> bit.ly/defensive-workflow </small>

![](https://goo.gl/fP43ed)



## Overview | <small> bit.ly/defensive-workflow </small>

* Overview the scientific workflow.

* Assess risks.

* Control risks with defensive tools and habits.



## The scientific workflow | <small> bit.ly/defensive-workflow </small>

* Enter data.

* Manage project.

<img src="https://goo.gl/rrK4ef" align="center" height=300 />
<small> [R for Data Science](http://r4ds.had.co.nz/) </small> 



## Risk assessment | <small> bit.ly/defensive-workflow </small>

![](https://www.stakeholdermap.com/risk/risk-assessment-matrix.png)



# Risks and controls | (tools and habits)

## Entering data: [Google sheets](https://www.google.com/intl/es/sheets/about/) | <small> bit.ly/defensive-workflow </small>

* Someone changed something they shouldn't: Protect Range.

* Some entered values are wrong: Data Validation.

* Discussing specific errors takes too long: Insert Comment.

Learn more: [G Suite Learning Center](http://bit.ly/2GL4sNo)



## Project management: [GitHub.com](https://github.com/) | <small> bit.ly/defensive-workflow </small>

* Loose your notes on ideas about a specific project: [Mastering Issues](https://guides.github.com/features/issues/) 
* Your inbox floods with emails on a project you don't care much about: [Managing your notifications](https://help.github.com/articles/managing-your-notifications/).
* Your cat eate your code and you want to go back in time: Git.

Learn more: 

* [What is GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E)
* [GitHub help)(https://help.github.com/)
* Webinar [GitHub and RStudio](https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-managing-part-2/)



## Project management: [RStudio projects](https://www.rstudio.com/) | <small> bit.ly/defensive-workflow </small>

* Your data, analyses, paper, and version control system become disconnected: Use RStudio projects.
* Loose track of how you cleaned raw data: Use rmarkdown documents.
* Loose track of different versions your data: Centralize data into an R packages.
* Loose track of what code produced which result: Tag each result.
* Your computing environment and that of your colleagues is different: Use rstudio.cloud.

Learn more:

* Webinar [Projects in RStudio](https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-managing-change-part-1/)
* [RStudio IDE Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)
* Webinar [Writing Code](https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-part-1/)
* Webinar [What’s New with the IDE](https://www.rstudio.com/resources/videos/whats-new-with-the-ide/)




# For R users | Skip in general discusisons



## Project management: [RStudio](https://www.rstudio.com/) | <small> bit.ly/defensive-workflow </small>

R objectes from previous sesisons contamine your R environment: Global options.

![](https://i.imgur.com/ywlwLq2.png)


```
## Installing package into '/home/rstudio-user/R/x86_64-pc-linux-gnu-library/3.4'
## (as 'lib' is unspecified)
```

```
## ● To start ALL RStudio sessions with a blank slate, you must set this interactively, for now.
## ● In Global Options > General, do NOT check "Restore .RData into workspace at startup".
## ● In Global Options > General, set "Save workspace to .RData on exit" to "Never".
## ● Call `use_blank_slate("project")` to opt in to the blank slate workflow in this project.
```

Learn more:

* Webinar [Projects in RStudio](https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-managing-change-part-1/)
* [RStudio IDE Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)
* Webinar [Writing Code](https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-part-1/)
* Webinar [What’s New with the IDE](https://www.rstudio.com/resources/videos/whats-new-with-the-ide/)



## Project management: rstudio.cloud | <small> bit.ly/defensive-workflow </small>

* An available computer may lack R and RStudio: Online access.
* Your code may behave differently in older R versions: Can choose version.
* An available computer may lack packages you need: Keeps packages.

Learn more: Video [Learning R with rstudio.cloud](https://www.rstudio.com/resources/videos/learning-r-with-rstudio-cloud/)



## Project management: here and rmarkdown | <small> bit.ly/defensive-workflow </small>

* Your code won't be reproducible if you set your working directory: Use `here::here()`.
* Your environment gets contamined quickly and code upstream may fail:
    * restart session often (Control + Shift + F10)
    * Use rmarkdown documents and notebooks
* You code comments don't poorly express your decisions: rmarkdown documents.

Learn more: 

* [Project oriented workflow](https://www.tidyverse.org/articles/2017/12/workflow-vs-script/), by Jenny Brian .
* [R Markdown Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf)
* [R Markdown Reference Guide](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf)
* [Getting Started with R Markdown](https://www.rstudio.com/resources/webinars/getting-started-with-r-markdown/)
* [Introducing Notebooks with R Markdown](https://www.rstudio.com/resources/webinars/introducing-notebooks-with-r-markdown/)



## TODO: Ask for help: reprex | <small> bit.ly/defensive-workflow </small>

TODO: Add content

Learn more: https://www.tidyverse.org/help/



### TODO: Installing packages | <small> bit.ly/defensive-workflow </small>

Tool: `installr::updater()`, __remotes__

* Struggle to install R-packages: `installr::updater()`, `remotes::install_github()`.

Learn more: My post on RStudio community



## TODO: Importing data | <small> bit.ly/defensive-workflow </small>

Tool: RStudio, readr

Learn more: my post on reading data with readr and base R.

* Webinar [Importing data into R](https://www.rstudio.com/resources/webinars/importing-data-into-r/)

* Cheetsheet [Data Import](https://github.com/rstudio/cheatsheets/raw/master/data-import.pdf)





# TODO: BACK TO GENERAL


# TODO: Back to general

## Summary: Software tools [![lifecycle](https://img.shields.io/badge/lifecycle-works_for_me-ff69b4.svg)](https://blog.codinghorror.com/the-works-on-my-machine-certification-program/) | <small> bit.ly/defensive-workflow </small>

Google sheets

GitHub

RStudio




## Digest | <small> bit.ly/defensive-workflow </small>

Design a defensive workflow, with tools and habits that facilitate key behaviors:

* Lower risks.
* Less frustration.
* Better research.



# Resources



## Human behaviour (and more) | <small> bit.ly/defensive-workflow </small>

My [audible library](http://bit.ly/share-wisdom) (also an example of a thoughfully crafted Google sheet)



## Curated resources to learn R | <small> bit.ly/defensive-workflow </small>

* Books:
    * [R for Data Science](http://r4ds.had.co.nz/)
    * [Advanced R](http://adv-r.had.co.nz/)
* Tutorials: [rstudio.cloud primers](https://rstudio.cloud/learn/primers)
* [RStudio webinars](https://www.rstudio.com/resources/webinars/)
* [Cheetsheets](https://www.rstudio.com/resources/cheatsheets/)



## Curated cheetsheets | <small> bit.ly/defensive-workflow </small>

* [RStudio IDE Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)
* [Data Transformations](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf)
* [R Markdown Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf)
* [R Markdown Reference Guide](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf)
* [Data Visualization Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf)
* [Apply Functions Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/purrr.pdf)
* [Work with Strings Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/strings.pdf)
* [Dates and Times Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/lubridate.pdf)



# 

end.



# Ideas

GENERAL
* Know your text editor (RStudio)
    * Know your shortcuts: Shift + Alt + K and search rstudio shortcuts online
    * rstudio keyboard shortcuts
    * RStudio IDE cheetsheet

* Ask for help
    * read help files `?`, `??` or help()
    * rubber ducking (explain your problem)
    * google
    * read stack overflow
    * read rstudio community
    * ask in rstudio community
    * reprex
  
HANDOUTS
RStudio IDE cheetsheet
