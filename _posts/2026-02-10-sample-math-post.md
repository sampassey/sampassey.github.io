---
layout: post
title: "A Quick Note on Euler Equations"
date: 2026-02-10
---

Here's a quick example of how math renders on this site.

Consider a representative household that maximizes lifetime utility

$$\max_{\{c_t\}_{t=0}^{\infty}} \sum_{t=0}^{\infty} \beta^t u(c_t)$$

subject to the budget constraint $a_{t+1} = (1+r)a_t + y_t - c_t$, where $\beta \in (0,1)$ is the discount factor.

The first-order condition gives us the standard Euler equation:

$$u'(c_t) = \beta (1+r) u'(c_{t+1})$$

With CRRA utility $u(c) = \frac{c^{1-\gamma}}{1-\gamma}$, this becomes

$$\left(\frac{c_{t+1}}{c_t}\right)^{\gamma} = \beta(1+r)$$

so consumption growth is constant along the balanced growth path.
