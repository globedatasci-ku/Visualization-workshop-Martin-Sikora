# Visualization workshop by Martin Sikora

In this workshop Martin gave some overview on how to create cool plots in ggplot2 and gave also some tips and tricks about how to make them look nicer. 

Here are some general links related to the ggplot and visualizations:

**Fundamentals of Data Visualization book:**

https://clauswilke.com/dataviz/

**R for Data Science book, chapter about the visualizations:**

https://r4ds.had.co.nz/data-visualisation.html

**The ggplot2 cheat cheet pdf link:**

https://raw.githubusercontent.com/rstudio/cheatsheets/main/data-visualization.pdf

The workshop has several excersizes built in the learnr package. You can either render it locally and run it from your computer or you can use the shiny version.

The first part is deployed here:

https://marianovosolov.shinyapps.io/03_dataviz/?_ga=2.59032100.82294288.1667913457-194285640.1667913457#section-welcome

The reproduction of the Novembre PCA plot is deployed here:

https://globedatasci-ku.github.io/Visualization-workshop-Martin-Sikora/10_analyze_novembre2008_full.html

Some more tips and tricks can be found here:


## Some more useful links related to what was discussed during the workshop:

Using unicode as shapes to expand the shapes selection we have:
- https://www.appsloveworld.com/r/100/368/r-ggplot2-shapes-in-unicode
- https://jtr13.github.io/cc21fall1/icons-and-symbols-in-r.html
- https://jrgraphix.net/r/Unicode/25A0-25FF

Color palettes:
- https://www.datanovia.com/en/blog/top-r-color-palettes-to-know-for-great-data-visualization/
- https://towardsdatascience.com/generating-color-palettes-in-r-64394117a662
- https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3
- https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html
- https://tmieno2.github.io/R-as-GIS-for-Economists/color-scale.html

Procrastes analysis - allows you to align PCA coordinates to other coordinates such as geographical (https://en.wikipedia.org/wiki/Procrustes_analysis):

- https://john-quensen.com/tutorials/procrustes-analysis/

Additional packages that use ggplot and build on top of it:

- ggforce (https://rviews.rstudio.com/2019/09/19/intro-to-ggforce/)
- ggrepel (https://ggrepel.slowkow.com/articles/examples.html)
- geomtextpath (https://github.com/AllanCameron/geomtextpath)


Useful geoms:

- geom_path (https://ggplot2.tidyverse.org/reference/geom_path.html)
- geom_segment (https://ggplot2.tidyverse.org/reference/geom_segment.html)
- geom_mark_hull (https://ggforce.data-imaginist.com/reference/geom_mark_hull.html)
- geom_sina (https://ggforce.data-imaginist.com/reference/geom_sina.html)
- theme_* (https://ggplot2.tidyverse.org/reference/ggtheme.html)
