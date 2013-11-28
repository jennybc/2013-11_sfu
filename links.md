Links
========================================================

[Hadley Wickham’s talk](https://dl.dropboxusercontent.com/u/41902/future-da-5-unconf.pdf) in the [Simply Statistics Unconference on the Future of Statistics](http://simplystatistics.org/unconference/)

Daring Fireball's [markdown page](http://daringfireball.net/projects/markdown/). Kind of where it all begins, but other references that are more recent and specific to our context are more relevant.

Carson Sievert's talk [Reproducible web documents with R, knitr & Markdown](http://cpsievert.github.io/slides/markdown/)

[MathJax](http://www.mathjax.org) is an open source JavaScript display engine for mathematics that works in all browsers ... It just works.

MathJax + RStudio specifics:

  * RStudio documentation page about [Equations in R Markdown](http://www.rstudio.com/ide/docs/authoring/using_markdown_equations)
  * Note that one should probably add a `latex` qualifier to equations that use the `$` or `$$` as delimiter in Markdown document. The simple demo from today worked fine without it but presumably that's not always true. Read the [RStudio blog announcement](http://blog.rstudio.org/2012/05/25/mathjax-syntax-change/) about this change.
  * Note that the multiline display equation in our simple demo used 4 backslashes to indicate line breaks. Presumably due to escaping issues, 2 backslashes were not enough to survive the conversion process and be seen by MathJax.

[Pandoc](http://johnmacfarlane.net/pandoc/): If you need to convert files from one markup format into another, pandoc is your swiss-army knife. 

[knitr](http://yihui.name/knitr/), an R package for elegant, flexible and fast dynamic report generation.

RStudio + R Markdown specifics:

  * <http://www.rstudio.com/ide/docs/authoring/using_markdown>
  * <http://www.rstudio.com/ide/docs/r_markdown>
  * <http://www.rstudio.com/ide/docs/authoring/markdown_notebooks>

Jeromy Anglim's blog post [Getting Started with R Markdown, knitr, and Rstudio 0.96](http://jeromyanglim.blogspot.ca/2012/05/getting-started-with-r-markdown-knitr.html)

How to change the CSS used when R markdown is converted to HTML

  * [Step-by-step instructions](http://www.stat.ubc.ca/~jenny/STAT545A/topic10_tablesCSS.html) from Jenny Bryan's STAT 545A course
  * <http://www.rstudio.com/ide/docs/authoring/markdown_custom_rendering>
  
