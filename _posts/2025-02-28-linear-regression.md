---
layout: post
title: Linear Regression Basics
date: 2025-02-28
---

# Linear Regression Basics

I'm exploring linear regression today—fitting a line to data points is fascinating!

## What It Is

The model is:
\( y = mx + b \)
where \( m \) is the slope and \( b \) is the intercept.

## Visualizing It

Here’s a diagram:
![Regression Plot](/assets/images/regression_plot.png)

## The Cost Function

We minimize the error with:
\[
J(\theta) = \frac{1}{2m} \sum_{i=1}^{m} (h_\theta(x^{(i)}) - y^{(i)})^2
\]
