---
title: What Is jekyll-latex?
author: John Doe
layout: post
---

# Introduction
Let’s say that we have some points that roughly look like they are forming a line. The goal of linear regression is to draw the line $$y = \beta_0 + \beta_1 x$$ that passes as close to these points as possible. It is a very straightforward simple linear approach for predicting a quantitative response $$Y$$ on the basis of a single predictor variable $$X$$. It assumes that there is approximately a linear relationship between X and Y .

## Definition Lists
First Term
: This is the definition of the first term.

Triple Integral
: $\iiint_V \mu(u,v,w) \,du\,dv\,dw$

: $ RSS = e_1^2 + e_2^2 + \ldots + e_n^2 = \sum_{i=1}^{n} (y_i - \hat{y}_i)^2 \tag{1} $

# Estimating the Coefficients  by the method of Least-Squares

Let $\hat{y}_i = \hat{\beta}_0 + \hat{\beta}_1 x_i$ be the prediction for $Y$ based on the $i$th value of $X$. Then $e_i = y_i - \hat{y}_i$ represents the $i$th residual—this is the difference between the $i$th observed response value and the $i$th response value that is predicted by our linear model. We define the residual sum of squares (RSS) as:

$$
RSS = e_1^2 + e_2^2 + \ldots + e_n^2 = \sum_{i=1}^{n} (y_i - \hat{y}_i)^2 \tag{1}
$$

: $ RSS = e_1^2 + e_2^2 + \ldots + e_n^2 = \sum_{i=1}^{n} (y_i - \hat{y}_i)^2 \tag{1} $

Alternatively, we can express RSS as:

$$
RSS = (y_1 - \hat{\beta}_0 - \hat{\beta}_1 x_1)^2 + (y_2 - \hat{\beta}_0 - \hat{\beta}_1 x_2)^2 + \ldots + (y_n - \hat{\beta}_0 - \hat{\beta}_1 x_n)^2.
$$


