+++
title = "My favorite things"

date = 2016-08-28
lastmod = 2018-01-28
draft = true

categories = ["meta"]
tags = ["meta"]
summary = "A continually updated list of learning resources, R packages, blogs, and related items which I find usefulblogging"

[header]
#image = "headers/getting-started.png"
#caption = "Image credit: [**Academic**](https://github.com/gcushen/hugo-academic/)"

math = true
+++

This is a collection of sites and resources I've found useful during my past work in statistics and data science. Bookmark folders are so passé.

## Online learning resources :earth_africa::bulb:

### Books written by Hadley Wickham 

- [R for Data Science](http://r4ds.had.co.nz)
- [R Packages](http://r-pkgs.had.co.nz)
- [Advanced R](http://adv-r.had.co.nz)

## Textbooks :book:

- [*The Elements of Statistical Learning* by Hastie, Tibshirani, and Friedman](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)
- [*The Bayesian Choice* by Christian Robert](https://errorstatistics.files.wordpress.com/2016/03/robert-20071.pdf) 

## Reference for `ggplot2` & visualization in R :chart_with_upwards_trend: 

I recommend to every R user, no matter their skill level, to take the plunge into using only `ggplot2` for producing visualizations in R. Yes, there's a learning curve, but in my opinion, once you learn the "grammar" behind it, you can make plots much more quickly because of the much greater consistency.

### `ggplot2`
- [R for Data Science, Chapter 3](http://r4ds.had.co.nz/data-visualisation.html): A good primer for begineers
- [Top 50 ggplot2 Visualizations](http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html): A great reference for producing a wide variety of data visualizations

### Visualization theory :bar_chart::thinking: 
- [Data Visualization: A practical introduction, by Kieran Healy](http://socviz.co): A good walkthrough of the "why" behind the grammar of graphics, instead of just the "how" (I still haven't come across a good explanation of `ggplot2`'s default use of a grey background, however...)
- [Practical Rules for Using Color in Charts](http://www.perceptualedge.com/articles/visual_business_intelligence/rules_for_using_color.pdf)

### Colors in R :heart::yellow_heart::green_heart::blue_heart::purple_heart:

- [R Colors](http://research.stowers.org/mcm/efg/R/Color/Chart/ColorChart.pdf): An exhaustive list of the default named colors in R, along with HEX and RGB codes 
- [`viridis` package](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html): "Use the color scales in this package to make plots that are pretty, better represent your data, easier to read by those with colorblindness, and print well in grey scale" 
- [`wesanderson` package](https://github.com/karthik/wesanderson): Color palettes inspired by the filmmaker Wes Anderson 
- [`RColorBrewer` package walkthrough](http://earlglynn.github.io/RNotes/package/RColorBrewer/index.html), with a good explanation of differences between and uses of qualitative, sequential, and diverging color palettes 
- [Colorbrewer 2.0: color advice for cartography](http://colorbrewer2.org/#type=qualitative&scheme=Set3&n=3)

## Reference for `Rcpp` and `RcppArmadillo` :computer:

- [`Rcpp` chapter in Advanced R](http://adv-r.had.co.nz/Rcpp.html): In my opinion, the best primer for Rcpp (even for C++ noobs)
- [`Rcpp` book by its creator Dirk Eddelbuettel](https://doc.lagout.org/programmation/Multi-Language/Seamless%20R%20and%20C%20%20%20Integration%20with%20Rcpp%20%5BEddelbuettel%202013-06-04%5D.pdf)
- [`Rcpp` Quick reference guide](http://dirk.eddelbuettel.com/code/rcpp/Rcpp-quickref.pdf)
- [`RcppArmadillo` examples from Dirk Eddelbuettel (slideshow)](http://dirk.eddelbuettel.com/papers/rcpp_ku_nov2013-part2.pdf)

## Blogs and feeds I follow :memo:

### Data science
- [#rstats on twitter](https://twitter.com/search?q=%23rstats&src=typd)
- [Hadley Wickham's twitter](https://twitter.com/hadleywickham)
- [David Robinson's blog](http://varianceexplained.org)

### Statistics
- [Andrew Gelman's blog](http://andrewgelman.com)
- [Deborah Mayo's blog](https://errorstatistics.com)

## Miscellaneous

- R styleguides. Yes, you should use one, just like you should always make your bed every morning.  
  - [Google's R styleguide](https://google.github.io/styleguide/Rguide.xml): Good enough for most cases.
  - [The tidyverse style guide](http://style.tidyverse.org): Based on Google's styleguide, this goes a bit more in depth. 
- Progress bars
  - [Base R](https://stat.ethz.ch/R-manual/R-devel/library/utils/html/txtProgressBar.html)
  - [`dplyr::progress_estimated()`](http://dplyr.tidyverse.org/reference/progress_estimated.html)
  - [Progress bars in `Rcpp`](http://gallery.rcpp.org/articles/using-rcppprogress/)
- [Use emojis for GitHub](https://www.webpagefx.com/tools/emoji-cheat-sheet/)

## For fun
["My Favorite Things" by John Coltrane](https://www.youtube.com/watch?v=YHVarQbNAwU)


