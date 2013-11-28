2013-11_sfu
===========

Supporting documents for talk and workshop for SFU Statistics

2013 November 29 (Friday)  

  * 1:30-2:30 Seminar, IRMACS Theatre
  * 2:30-3:30 Informal Open Workshop, IRMACS Theatre

Part of a "[special Seminar series this fall](http://stat.sfu.ca/news/fallseminar.html), organized by and for students. To celebrate the International Year of Statistics and recognize the contribution of Statistics to society, the series will feature interdisciplinary speakers and talks with a career component." [PDF](http://stat.sfu.ca/content/dam/sfu/stat/news/seminar2013Fall.pdf) for the series

## Preparation for workshop

### R and RStudio

Download and install [R, a free software environment for statistical computing and graphics](http://www.r-project.org) from [CRAN](http://cran.rstudio.com), the Comprehensive R Archive Network. It is _highly recommended_ to install a precompiled binary distribution for your operating system -- use the links up at the top of the CRAN page linked to above!

Install RStudio, a powerful user interface for R: <http://www.rstudio.com/ide/download/>. If you wish, you can read more about how to use RStudio [here](http://www.rstudio.com/ide/docs/). It's fairly self-explanatory and we will point out major features.

### Testing testing

* Do whatever is appropriate for your OS to launch RStudio. You should get a window similar to the screenshot you see [here](http://www.rstudio.com/ide/), but yours will be more boring because you haven't written any code or made any figures yet!

* Put your cursor in the pane labelled Console, which is where you interact with the live R process. Create a simple object with code like `x <- 2 * 4` (followed by enter or return). Then inspect the `x` object by typing `x` followed by enter or return. Obviously you should see the value 8 print to screen. If yes, you are good to go.

## Add-on packages

R is an extensible system and many people share useful code they have developed as a _package_ via CRAN and github.

Please install the [`knitr` package](http://yihui.name/knitr/) for report generation and its dependencies. Here is one way to do it in the R console (there are others):

```
install.packages("knitr", dependencies = TRUE)
```

We will also be joined by Scott Chamberlain from [rOpenSci](http://ropensci.org), who will share a short demo. To follow along in this section, please install the packages `rplos` (for retrieving literature data from the Public Library of Science) and `tm` (for text mining). Again, here is code that will do the installation:

```
install.packages(c("rplos", "tm"))
```

## Optional but recommended: get an account on RPubs

Sign up for a free account at [Rpubs.com](http://rpubs.com). This will allow you to easily publish automatically generated reports, written in R Markdown or plain R, at the click of a button in RStudio.

## Optional: get an account on GitHub

We will not be able to delve deeply into version control in this short workshop. But we will spend some time looking at Git and GitHub, so if anyone wants to dip their toe in, go ahead and get an account on GitHub. This is completely optional and costs nothing. Go here: [https://github.com](https://github.com).

Students may want to get an educational account at [github.com/edu](https://github.com/edu). What is different between an educational account and a regular account? With a regular account you must pay for *private* repositories (public repositories are free and unlimited). With an educational account, you get a small number of private repositories free for a couple of years.

## Very very optional: install Git

This is more for the future, as we cannot cover Git in the workshop. But when you are ready, here are leads on installing Git (taken from <http://www.rstudio.com/ide/docs/version_control/overview>):
  * Windows: http://code.google.com/p/msysgit/
  * OSX: http://code.google.com/p/git-osx-installer/
  * Debian/Ubuntu: sudo apt-get install git-core
  * Fedora/RedHat: sudo yum install git-core

I highly recommend using a Git GUI, especially at the beginning. I am very happy with the free [SourceTree](http://www.sourcetreeapp.com) Git client. Available for Windows or Mac.
