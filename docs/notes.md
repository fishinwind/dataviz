
# Notes

## Outline

\*Chapter started; made relevant figures and/or wrote rudimentary first draft  
\*\*Chapter mostly complete

### Part I: General principles of figure design {-}

#. **Visualizing data: mapping data onto aesthetics**  
  Explains the basic concept of aesthetic mapping, which lies at the heart of any data visualization.

#. **Choosing colorblind-friendly color scales**\*  
  Explains what color choices can and cannot be seen by people with colorblindness, and also introduces the three basic types of color scales: qualitative, directional, diverging. Material on diverging color scales is not yet written. 

#. **Effective use of color in figures**  
  Covers basic concepts of color use, as a tool to highlight, as a tool to distinguish, and as a tool to represent a value.

#. **Redundant coding**\*
  Explains how to make sure that key information in the figure is provided in multiple, reduant ways, for example through color and location or color and direct labeling.

#. **Your axis labels are too small**\*\*  
  Discusses the widespread problem of excessively small axis labels.
  
#. **Choosing the right axis settings**  
  Covers various aspects related to axis choice, including linear vs. logarithmic axes, as well as issues of axis expansion beyond the data range.

#. **Choosing an appropriate aspect ratio**  
  Discusses the concept of aspect ratio, including when it matters a lot (same axis range on x and y) and when it is more of a personal preference.

#. **Background grids**\*\*  
  Discusses when and how to use background grids and other guide lines in figures.

#. **Don't box yourself in**  
  Argues to avoid boxes and frames around figure parts.
  
#. **Avoid line drawings**  
  Argues that filled shapes and solid colors are almost always preferable to shapes shown as outlines or with hatching or cross-hatching.

#. **Handling overlapping points**\*  
  Describes different strategies to handle the problems of overlapping points or large point clouds. These problems frequently arise in large datasets, and helpful strategies include using partially transparent points, 2d density plots, hex grids, or smoothers.
  
#. **Multi-part figures**  
  Discusses issues that arise in multi-part figures, including proper labeling, alignment between subfigures, shared legends, and overly complex multi-part figures. 
  
#. **Don't go 3d**  
  Argues why 3d plots are generally problematic (figures are fundamentally a 2d medium, and in 3d plots data is subjected to an additional, non-obvious transformation from 3d to 2d) and suggests alternatives to visualize high-dimensional datasets, including encoding additional variables in color, size, or symbol shape, and/or using faceting.
 
### Part II: A figure for every occasion  {-}

14. **Directory of visualizations**\*  
  Provides a graphical guide to the most commonly used types of data visualizations, with pointers to relevant other chapters in the book.
  
#. **Visualizing paired data**  
  Discusses common strategies for paired data, including scatter plots and paired dot plots.

#. **Visualizing time series**  
  Discusses common strategies for time series, including line plots and sparklines

#. **Visualizing trends**  
  Discusses various approaches to smoothing data (linear regression line, GAMs, splines), and common pitfalls (many smoothers are unreliable or misleading at the edges of the data range).

#. **Visualizing distributions I: Histograms and density plots**  
  Discusses strategies for visualizing individual distributions, including pros and cons of histograms and density plots.

#. **Visualizing distributions II: Boxplots, violin plots, and more**\*  
  Discusses strategies for visualizing many distributions, including boxplots, violin plots, jittered points, and others.

#. **Visualizing distributions III: Joyplots**  
  Describes the joyplot, an effective tool for visualizing a very large number of related distributions.

#. **Visualizing proportions**  
  Discusses bar plots, stacked bar plots, stacked density plots, and pie charts.
  

### Part III: Miscellaneous topics {-}

22. **Understanding the most commonly used image file formats**\*\*  
  Provides an introduction to vector and bitmap graphics and describes the pros and cons of the various most commonly used file formats.

#. **Choosing the right plotting software**  
  Discusses the pros and cons of different software available to make graphs.
  
#. **Annotated bibliography**  
  Provides a list of other reading material on related topics, with a brief paragraph describing the contents of each reference.
  
  
  
## Other notes and comments

- for paired data chapter, use protein correlation dataset from Echave et al?
- need a clear system of stamping figures while keeping some spacing. current system is ad-hoc and inconsistent. This touches all chapters already written.
- aspect ratio chapter needs to be completed
- in the colorblind package, add color simulations using the dichromat R package?
- this looks like a useful resource: [dataviz catalogue](http://www.datavizcatalogue.com/about.html)
- the [viridis package](https://CRAN.R-project.org/package=viridis) has several great color scales

Articles and blog posts with useful ideas:

- https://medium.com/@clmentviguier/how-to-turn-a-twitter-comment-into-a-data-visualisation-design-opportunity-7447402f0c2f
- http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html

Datasets to use:

- midwest (ggplot2)
- overlapping points: mpg cty vs hwy
- economics (ggplot2)