---
title: "Gradient Descent"
author: "Jimmy Hickey"
date: "2020-03-31"
output: 
 html_document:
  css: css/main.css
  theme: flatly
  highlight: tango
  toc: true
  toc_float:
   collapsed: true
   smooth_scroll: false
  fig_width: 7
  fig_height: 5
  fig_caption: true
  code_folding: show
  keep_md: true
---

+++






```r
## Number of International Calls from Belgium,
## taken from the Belgian Statistical Survey,
## published by the Ministry of Economy,
##
## 73 subjects, 2 variables:
##  Year(x[i])
##  Number of Calls (y[i], in tens of millions)

## Provided on-line at the University of Cologne.

x <- c(50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68,
  69, 70, 71, 72, 73)

y <- c(0.44, 0.47, 0.47, 0.59, 0.66, 0.73, 0.81, 0.88, 1.06, 1.20, 1.35, 1.49, 1.61,
  2.12, 11.90, 12.40, 14.20, 15.90, 18.20, 21.20, 4.30, 2.40, 2.70, 2.90)
```

# What is Gradient Descent?



## Exposition

## Formulate problem

## Derivation


## Why Gradient Descent?

# Examples + Code


## Quick example from homework


## Strongly Convex function

"Maybe some numerical experiments illustrating the convergence properties of applying gradient descent on a strongly convex function."


# When it doesn't work / setbacks

## Issues with gradient descent

## Function it doesn't apply to / violates assumptions




# Alternatives

## Newton / Quasi-Newton Methods
