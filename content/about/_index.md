+++
date = "2020-06-28T12:05:33+05:30"
title = "About"
+++

## Introduction

This site is a gallery for R Markdown templates/themes. Currently, 131 [templates/themes](../../portfolio) are collected, including 22 [packages](../../categories) classified in 12 [groups](../../tags).

[R Markdown](https://rmarkdown.rstudio.com/) is a fantastic toolbox in the [R](https://cran.r-project.org/) community. With R Markdown, you can produce a variety of reproducible documents for communication, including reports, scientific manuscripts, journal articles, theses, books, posters, slides, websites, etc., even if you do not know how to use R itself. They are platform-independent. This ecosystem is still growing fast. R Markdown is a demonstration that shows how much amazing work R can do besides data processing and visualization.

The R Markdown world is huge. After years of using R Markdown, I collected many nice packages, templates, and themes. I found it, however, painful to search a suitable template/theme before I started writing something. Sometimes it was like searching the ocean for a needle. I knew it was somewhere, but I had no idea where it was.

The other day @[Cloud2016](https://d.cosx.org/u/Cloud2016) shared [another nice beamer template](https://d.cosx.org/d/421591). I raised the question again, "how do you guys organize your collection of templates?" Later an idea came into my mind: why not build a website?

That is basically why you see this site.

On this site you can view the R Markdown templates by groups, see the live demos, and share your new discoveries. This is still far from a complete collection of R Markdown, thus your recommendations would be appreciated. 

Note that the R blogdown package is not displayed on this website, as the [Hugo theme gallery](https://themes.gohugo.io/) is already available. 

## Navigation

There are five buttons at the sidebar.

- [Class](https://rmd.pzhao.org/tags/): Group the R Markdown templates/themes by document type.
- [Packages](https://rmd.pzhao.org/categories/):  Group the R Markdown templates/themes by R packages.
- [Gallery](https://rmd.pzhao.org/portfolio/): Display the thumbnails of all. Caution! It takes time to load all.
- [About](https://rmd.pzhao.org/about/): Show how to use this site.
- [Contact](https://rmd.pzhao.org/contact/): Send me an email if you would like to share something.

On the template page, you can find the thumbnail, the package name, the author, the link to the project webpage, and the link to the demonstration (if any).

## How to use

1. You have to install R and the R package which contains the template of interest. 
   - For installing R, see [CRAN](https://cran.r-project.org/).
   - For installing the R package, run `install.packages("package_name")` if it is on CRAN. Otherwise, check the project webpage for help.
   - For creating pdf documents, the R package [tinytex](https://yihui.org/tinytex/) is recommended. After installing tinytex, run `tinytex::install_tinytex()` for installing a smart distribution of LaTeX.
2. The installation of [RStudio IDE](https://rstudio.com/products/rstudio/download/#download) is not a must, but recommended. The subsequent steps are described on the basis of RStudio IDE. If you don't use it, please visit the package webpage for help.
3. Open RStudio IDE, click the "New File" button and choose "R Markdown". In the "From Template" tab, choose the template you want.

[![Step 1](https://camo.githubusercontent.com/afb001676afee338971905331ba80f4a0c82d922/68747470733a2f2f707265747479646f632e73746174722e6d652f696d616765732f73746570312e706e67)](https://camo.githubusercontent.com/afb001676afee338971905331ba80f4a0c82d922/68747470733a2f2f707265747479646f632e73746174722e6d652f696d616765732f73746570312e706e67)



[![Step 2](https://camo.githubusercontent.com/09f94a0a140e63a5d0770b7429d005822c9a2eea/68747470733a2f2f707265747479646f632e73746174722e6d652f696d616765732f73746570322e706e67)](https://camo.githubusercontent.com/09f94a0a140e63a5d0770b7429d005822c9a2eea/68747470733a2f2f707265747479646f632e73746174722e6d652f696d616765732f73746570322e706e67)

4. Once inside your new `.Rmd` file, you should see some boilerplate text that includes code chunks. Use the "Knit" button in the RStudio IDE to render the file and preview the output with a single click or use the keyboard shortcut Cmd/Ctrl + Shift + K.
5. Once a demonstration document is successfully created, you can delete all the text below the YAML frontmatter and fill in your own `.Rmd` by:
   - Adding code chunks (keyboard shortcut: `Ctrl + Alt + I`; OS X: `Cmd + Option + I`),
   - Writing prose with [Markdown formatting](https://www.markdowntutorial.com/).

For more help getting started in R Markdown, please see the [R Markdown website](https://rmarkdown.rstudio.com/lesson-1.html), or read the following materials.

## Learning materials

<p><a href="https://bookdown.org/yihui/rmarkdown/"><img class = "jf-image-shadow" src="https://openr.pzhao.org/slides/cufe2020/resource/book-rmarkdown.jpg" width="60%"  align="left"></a></p>

<p><a href="https://bookdown.org/yihui/rmarkdown/"><img class = "jf-image-shadow" src="https://openr.pzhao.org/slides/cufe2020/resource/book-bookdown.jpg" width="60%"  align="left"></a></p>

<p><a href="https://bookdown.org/yihui/blogdown/"><img class = "jf-image-shadow" src="https://openr.pzhao.org/slides/cufe2020/resource/book-blogdown.jpg" width="60%"  align="left"></a></p>

<p><a href="https://xuer.pzhao.org"><img src="https://openr.pzhao.org/slides/cufe2020/resource/xuer.jpg" width="60%"  align="left"></a></p>


