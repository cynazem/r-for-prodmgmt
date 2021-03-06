# R for Product Management

## Background
### Aims
Produce a repository of useful scripts in R for Product Managers

### Audience
As the name suggests, Product Managers dealing with data that want to use R as a tool to analyse that data and produce reports/visualisations. If you haven't used R before then the first step will be to install R, for example:

* Local install on Windows
  * Install R from https://cran.r-project.org/bin/windows/base/
  * Install RStudio from https://www.rstudio.com/products/rstudio/download/
* Install in Cloud9
  * [StackOverflow answer on how to use R and Cloud9](https://stackoverflow.com/questions/36897276/how-to-install-r-on-the-cloud-9-ide)
  
 The scripts should work pretty much unaltered from source, but if you want to edit them you'll need some background. For a taster these intro courses are free:
 * [Try R at Codeschool](https://www.codeschool.com/courses/try-r) is a good intro that covers wide range of topics, but without much depth
 * [Introduction to R at Datacamp](https://www.datacamp.com/courses/free-introduction-to-r) gives a much deeper understanding of data types and R structure.
 * [Beginner's guide to R: Introduction](https://www.computerworld.com/article/2497143/business-intelligence/business-intelligence-beginner-s-guide-to-r-introduction.html) is more a reference than the two interactive courses above, ideal to skim if you have some scripting experience already

I already used Sublime as my text editor and can recommend [R-Box](https://github.com/randy3k/R-Box) to improve the R support - e.g. it adds R Markdown syntax highlighting.

## Reports
## Google Analytics
This first section has some reports to get usage stats from Google Analytics, an example Shiny app for some data exploration using data controls, and a template R Markdown report to show how this data can be manipulated and presented.

## Elasticsearch
Example analysis of components and logging output, including relative error rates - Coming soon

## InfluxDB
Working with time series data generated by the product, the two examples here are API response times and feature usage. This includes an example of manipulating time series data to set missing values to 0 for plotting. 

## UptimeRobot
Simple example of taking error data and using a pivot table to explore the data, after some cleaning and filtering. This kind of workflow can be useful with large data sets.
