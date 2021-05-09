---
title: Polar Coordinates
author: Mathew Gluck
date: '2021-05-02'
slug: polar-coordinates
categories: []
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: '2021-05-02T22:57:20-04:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

In the front matter, I should always write a few words to fill up the preview lines. Nothing technical, no equations, etc. The equations and technical content seem to have trouble rendering in the preview. 

## Coordinate Transformations

The _polar-to-rectangular_ coordinate transformation is 
$$
\begin{cases}
    x = r\cos \theta\\\\ % need extra line break
    y = r\sin \theta. \\\\
\end{cases}
\label{eq:trans}
$$
The reason for this name (as opposed to rectangular-to-polar) is if we know the polar coordinates $(r, \theta)$ of a point in the plane then we can substitute these coordinates into equations \eqref{eq:trans} to immediately recover $x$ and $y$; no solving, just immediate recovery.  

\eqref{eq:trans}

The polar coordinates $(r,\theta)$ measure the signed distance from a point $P$ to the pole and the angle from the polar axis to the segment joining $P$ to the pole. The polar-to-rectangular coordinate tranformation is
$$
\label{eq:not_rect_to_polar}
\begin{split}
    r^2 \& = x^2 + y^2\\\\ % need extra line break
    \tan \theta \& = \frac y x\\\\
\end{split}
$$

So now my equations are rendered wiht numbers. Here is a reference: \eqref{eq:1}

I think the $\LaTeX$ symbols `&` mess with the equation labeling. 
$$
\begin{cases}
    r^2 \& = x^2 + y^2\\\\ % need extra line break
    \tan \theta \& = \frac y x\\\\
\end{cases}
\label{eq:a}
$$

\begin{equation}
\begin{cases}
    r^2  = x^2 + y^2\\\\ % need extra line break
    \tan \theta  = \dfrac y x\\\\
\end{cases}
\label{eq:b}
\end{equation}


The center of mass of a collection of points $\{(x_i, y_i)\}\subset \mathbb R^2$ is $(\overline x, \overline y)$ where
\begin{equation*}
    \overline x = \frac 1 n\sum_{i = 1}^n x_i
\end{equation*}

















