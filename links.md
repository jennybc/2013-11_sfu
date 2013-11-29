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

Jeromy Anglim's blog post [Getting Started with R Markdown, knitr, and Rstudio 0.96](http://jeromyanglim.blogspot.ca/2012/05/getting-started-with-r-markdown-knitr.html) and a [Gist containing the source](https://gist.github.com/jeromyanglim/2716336)

How to change the CSS used when R markdown is converted to HTML

  * [Step-by-step instructions](http://www.stat.ubc.ca/~jenny/STAT545A/topic10_tablesCSS.html) from Jenny Bryan's STAT 545A course
  * <http://www.rstudio.com/ide/docs/authoring/markdown_custom_rendering>
  
[RPubs](http://rpubs.com)

  * [Jenny's profile](http://rpubs.com/jennybc)
    - [HTML based on simple-markdown.md](http://rpubs.com/jennybc/simple-markdown)
    - [HTML based on simple-r-markdown.md](http://rpubs.com/jennybc/simple-r-markdown)
    - [HTML based on `toyline.R`](http://rpubs.com/jennybc/toyline)
  * Windows users may run into an SSL certificate problem when first attempting to upload to RPubs. Here is advice developed by the long suffering students in STAT 545A:
    - Your basic solution can be found [here](http://support.rstudio.org/help/discussions/problems/2513-problem-with-publish-to-rpubs-windows-rstudio-096231)
    - You will need to add the line `options(rpubs.upload.method = "internal")` to the file `Rprofile.site` which will live somewhere like this: `C:\Program Files\R\R-3.0.1\etc`. Yes take the `etc` __literally__. There is a directory with this name.
    - You will need administrator access to edit this file, which you can get by right licking and choosing "Run as administrator" when you launch whatever you're going to use for editing.
    - Do not edit something like this with (eeeeekkk) Word. Use Notepad or even the RStudio editor. Plain text editing!
    - Another way to get permission to edit this file: Right click on the file, choose "Properties"--> "Security", and Edit to give "Full control" to "Users". Then you will be given the permission to edit the file.
    
Ram, K 2013. Git can facilitate greater reproducibility and increased transparency in science. Source Code for Biology and Medicine 2013 8:7. Go to the [associated github repo](https://github.com/karthikram/smb_git) to get the PDF (link at bottom of README) and to see a great example of how someone managed the process of writing a manuscript with git(hub).

Karl Broman's tutorial, aimed at stats / data science types: [An introduction to Git/Github](http://kbroman.github.io/github_tutorial/).

[SourceTree](http://www.sourcetreeapp.com) Git client, with a GUI. Available for Windows or Mac.

RStudio + Git(Hub)
  * <http://www.rstudio.com/ide/docs/version_control/overview>

Funnies

  * ["FINAL".doc comic from PhD comics](http://www.phdcomics.com/comics/archive.php?comicid=1531)
  * [xkcd on Git commit messages](http://xkcd.com/1296/)
  