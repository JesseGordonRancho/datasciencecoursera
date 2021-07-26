---
  title: "HelloWorld for Coursera"
author: "JesseGordon"
date: "7/26/2021"
output: html_document
---
  
  ```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)

## This is a markdown file 
install.packages("ggplot2") 
library (ggplot2)
print ("hello world")

example <- matrix (c(1, 2.55, 3.5, 4.6, 5, 6.66, 7, 8), nrow=4, ncol=2)

example2 <- matrix (c(1, 2, 3, 4, 5, 6, 7, 8), nrow=4, ncol=2)
# num [1:4, 1:2] 1 2 3 4 5 6 7 8  

```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:
  
  ```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:
  
  ```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
