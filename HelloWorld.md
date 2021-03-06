---
title: "rdoc1"
author: "varun"
date: "06/03/2021"
output: pdf_document
## This is a markdown file
---

```
```
```{r}
print("Hello World")



```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.
```{r}

```
Bold text-use ** **
eg **Varun**
for italics
*Varun*
for bullets <sapce> -
eg
- Varun

```{r}

```


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