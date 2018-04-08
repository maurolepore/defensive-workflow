---
title: "Defensive workflow"
subtitle: Risk assessment, tools, and habits for better research
author: https://bit.ly/mauro_lepore
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

-----------------










# Risks, tools and habits

## Entering data | <small> bit.ly/defensive-workflow </small>

Tool: [Google sheets](https://www.google.com/intl/es/sheets/about/)

Risk: Control

* Someone changed something they shouldn't: Protect Range.

* Some entered values are wrong: Data Validation.

* Discussing specific errors takes too long: Insert Comment.

Learn more: [G Suite Learning Center](http://bit.ly/2GL4sNo)




## Project management | <small> bit.ly/defensive-workflow </small>

Tool: [GitHub.com](https://github.com/)

Risk: Control

* Loose your notes on ideas about a specific project: [Mastering Issues](https://guides.github.com/features/issues/) 

* Your inbox floods with emails on a project you don't care much about: [Managing your notifications](https://help.github.com/articles/managing-your-notifications/).

* Your cat eate your code and you want to go back in time: Git.

Learn more: 

* [What is GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E)

* [GitHub help)(https://help.github.com/)

* Webinar [GitHub and RStudio](https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-managing-part-2/)



## Project management | <small> bit.ly/defensive-workflow </small>

Tool: RStudio, rstudio.cloud, __here__, rmarkdown documents


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

* Webinar [Writing Code](https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-part-1/)

* Webinar [What’s New with the IDE](https://www.rstudio.com/resources/videos/whats-new-with-the-ide/)

* Webinar [Projects in RStudio](https://www.rstudio.com/resources/webinars/rstudio-essentials-webinar-series-managing-change-part-1/)


* [rstudio.cloud](https://rstudio.cloud/)


* RStudio IDE cheetsheet
* RStudio IDE webinar
* Jenny Bryan's slides (somewhere)

Problems and solutions:

* R environment is contamined:
    * Use rstudio.cloud
    * Don't save history nor use data from previous sesions: `usethis::use_blank_slate()`.
    * use rmarkdown documents to force you start with fresh environment.
    * restart session with Shift + Control + F10.
    
* Project is not reproducible because paths are absolute: Use paths relative to .proj (__here__).

### Ask for help | https://www.tidyverse.org/help/

![](https://nypdecider.files.wordpress.com/2014/08/help-me-help-you.gif)

### Ask for help | example

```R
remove.packages("reprex")
install.packages("reprex")
```

Try example at https://www.tidyverse.org/help/

Google error and reach [rstudio community](https://community.rstudio.com/t/reprex-error-no-input-provided-and-clipboard-is-not-available/5197)

```R
devtools::install_github("tidyverse/reprex")
```

### Installing packages

Tool: `installr::updater()`, __remotes__

* Struggle to install R-packages: `installr::updater()`, `remotes::install_github()`.

Learn more: My post on RStudio community






### Importing data

Tool: RStudio, readr

Learn more: my post on reading data with readr and base R.

* Webinar [Importing data into R](https://www.rstudio.com/resources/webinars/importing-data-into-r/)


* Cheetsheet [Data Import](https://github.com/rstudio/cheatsheets/raw/master/data-import.pdf)

TOOLKIT
Google docs
Google sheets
GitHub
RStudio


MOTIVATE
Motivate by showing how powerful the editor is. Create an outline
of the course on the fly, and publish it.
* Start a google document
* Create a quick link
* Ask what people think a defensive workflow is
* Create a GitHub repo
* Link it with RStudio cloud
* Create an Rmd document, and paste the key ideas


SPECIFIC
Refresh R session often (many times per hour). Shift + Control + F10


GENERAL
* Know your text editor (RStudio)
    * Rstudio Webinars
        * IDE - early webinar
        * What's new in ... recent webinar.

* Know your shortcuts. 
    * Shift + Alt + K and search rstudio shortcuts online
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

IDEAS
Show fast so that some students get lost. Then regroup class so that
students help each other.









-----------------

## Summary: Software tools [![lifecycle](https://img.shields.io/badge/lifecycle-works_for_me-ff69b4.svg)](https://blog.codinghorror.com/the-works-on-my-machine-certification-program/) | <small> bit.ly/defensive-workflow </small>

* Google sheets

* GitHub

* RStudio

## Summary: Cognitive tools [![lifecycle](https://img.shields.io/badge/lifecycle-works_for_me-ff69b4.svg)](https://blog.codinghorror.com/the-works-on-my-machine-certification-program/) | <small> bit.ly/defensive-workflow </small> 

* Tools: RStudio webinars

* Habits: James Clear

References (and free audible books): http://bit.ly/share-wisdom



## How can you improve your workflow ? | <small> bit.ly/defensive-workflow </small>

* Design a defensive workflow, with tools and habits that facilitate key behaviors:

    * Lower risks.
    
    * Less frustration.
    
    * Better research.


# Resources | R

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


