![uzk_logo](../uzk.png)

# Programming Data Science

Homework for week 3

Topic of the week: The layered grammar of graphics

Learning objectives:

```text
> Students will learn...
- how the grammar describes a plot
- how it is implemented in R and in Python
- how to make complex graphs with GGplot and Plotnine
```

## What do I have to prepare?

1. Think about the last time you have prepared a scientific graph (for example for a seminar paper or a thesis). What was the process of creating the graph like? Which steps were involved? How happy are you with the tool you have used (EXCEL, SPSS, GnuPlot, STATA, ...)?  

2. Contrast your experience with the layered grammar of graphics. For this, read Grolemund and Wickham, chapter three carefully. How do the elements of the grammar work together to describe a graph? 

3. Install R, Rstudio, the `tidyverse` and work through exercises 3.2.4 (all questions). 

4. The golden rule: All programming in R and Python, please. Install `plotnine` and Python (v. 3.5 or higher). Then do the _same_ with plotnine. Yes, please.

By now, you should be able to plot in R and in Python! Congratulations. There are many ways to proceed from here. Pick one route, depending on how much you know.

* "I um uncertain, this is quite hard. I need step-by-step problems and solutions." No worries! Go to Step 5.
* "I think I get it. Let me practice, and I will be fine". Great, go to Step 6. 
* "Nah, too simple. Gimme more." Sure, see Step 7. 

5. Easy route: The safest way to learn is to do and then correct mistakes. Please work through the chapter carefully and try to replicate all code that you see in the book in R. That also means that you should answer the questions at the end of the subsections. The questions are simple at the beginning and are gradually becoming harder. How do you know you got the answer right? Discuss your solution with your team members (preferred). If that is not an option, there is a site that has solutions to most problems. [Check it out.](https://jrnold.github.io/r4ds-exercise-solutions/). Or you code in Python, and compare the results. This is very helpful!

6. Intermediate: read the chaper, read through the exercises. Answer the hard ones and compare your answers with your colleagues. Then, try to replicate the following complex graphs step-by-step, by following the tutorials! Are there differences between the R and Python outputs?

A complex bar chart, [click for tutorial.](http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html) 

![cars data](http://r-statistics.co/screenshots/ggplot_masterlist_34.png)

A bubble plot, [click for tutorial.](http://t-redactyl.io/blog/2016/02/creating-plots-in-r-using-ggplot2-part-6-weighted-scatterplots.html)

![bubble plot](http://t-redactyl.io/figure/wscatter_finalgraph-1.png)

Tips by day and gender, [click for tutorial](http://www.cookbook-r.com/Graphs/Facets_(ggplot2)/)

![tips](http://www.cookbook-r.com/Graphs/Facets_(ggplot2)/figure/unnamed-chunk-6-1.png)

7. Advanced: read through the chapter, choose one of the previous images, and try to replicate it __without__ the tutorial. Then, take a look at the following graph. Can you do that as well? Replicate it with your own code (do not follow the tutorial). Python and R, please. 

![hist with binning](http://r-statistics.co/screenshots/ggplot_masterlist_19.png)

Come up with suggestions that make the graph better. What could you improve?

## What if I want to know more?

The following resources will provide background information, a broader perspective, or more details. Although you do not have to go through these materials, if you want to know more, they might be interesting.

1. There are many geoms. Which one should you pick? Check out the following visual vocabularies:

* https://gramener.github.io/visual-vocabulary-vega/#
* https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary

2. Hadley Wickham: [A layered grammar of graphics](https://vita.had.co.nz/papers/layered-grammar.html)

2. I found out about the good [R Graphics Cookbook](https://r-graphics.org/) too late to include it in the lecture somehow. Read it online for free.