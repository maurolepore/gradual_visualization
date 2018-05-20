A gRadual intRoduction to data visualization
================
Chester Ismay and Ted Laderas

Welcome! This is a workshop for the Cascadia R conference that is meant to be a gentle introduction to data visualization using the `ggplot2` and the `plotly` packages.

You'll learn the basics of the grammar of graphics and learn how to visualize and understand relationships between different kinds of variables in your dataset.

Prerequisites
-------------

Please make sure to have this completed prior to the workshop beginning. To participate in this workshop, you'll need to do the following on your own laptops:

-   Have the latest version of R AND RStudio installed ([Directions are here](http://moderndive.netlify.com/2-getting-started.html#what-are-r-and-rstudio))
-   Be familiar with the [basics of the RStudio Interface](https://ismayc.github.io/rbasics-book/3-rstudiobasics.html#rstudio-layout)
-   (Optional) The workshop materials will be presented in R Markdown format. You may want to read a little more about this [here](https://ismayc.github.io/rbasics-book/4-rmarkdown.html) before the workshop begins and play around with R Markdown documents some first.
-   Have the following R packages installed:
    -   `tidyverse`, `plotly`, `gapminder`, and `fivethirtyeight`

This can be accomplished by copying the following code into the *Console* in RStudio and pressing Enter. Note that you'll see quite a few lines of code run while the packages are installing. Don't be alarmed. After all four of these packages are installed you should see them listed in the Packages tab in the bottom right section of RStudio.

    install.packages(c("tidyverse", "plotly", "gapminder", "fivethirtyeight"))

-   The [`tidyverse`](http://tidyverse.tidyverse.org/) package installs a variety of different packages that will be useful in your analysis including the [`ggplot2`](https://ggplot2.tidyverse.org/) package that will be the focus of this workshop.
-   The [`plotly`](https://plotly-book.cpsievert.me/) package will be used for interactive graphics.
-   The [`gapminder`](https://github.com/jennybc/gapminder/blob/master/README.md) package contains a data set made famous by Hans Rosling exploring data on the world's countries.
-   The [`fivethirtyeight`](http://fivethirtyeight-r.netlify.com/) package contains many datasets used by data journalists at FiveThirtyEight.com.

Remember, in this workshop we will adhere the [code of conduct for this conference](https://cascadiarconf.com/coc/). Be respectful of your fellow students and let's learn together.

Outline of this Workshop
------------------------

1.  Visualizing continuous data (scatterplots)
    -   Learning about `aes`thetics and `mapping` of variables
    -   Some basic `geom`etries
2.  Visualizing categorical data
    -   More about `geom`s
    -   Learning about create small multiple plots using `facet`ing
3.  Visualizing categorical versus continuous data (boxplots)
4.  Making your plots interactive using the `ggplotly()` function in the `plotly` package
