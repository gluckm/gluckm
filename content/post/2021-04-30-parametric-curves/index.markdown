---
title: Parametric Curves
author: Mathew Gluck
date: '2021-04-30'
slug: parametric-curves
categories: []
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: '2021-04-30T18:28:09-04:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---
# Overview 
A parametric curve is a curve in `$\mathbb R^2$` \$\mathbb R^2\$ together with infomration regarding how the curve is traversed. 



<div class="definition"><span class="definition" id="def:unnamed-chunk-1"><strong><span id="def:unnamed-chunk-1"></span>Definition 1  </strong></span>A <em>planar parametric curve</em> is a function defined on some subinterval <span class="math inline">\(I\subset \mathbb R^2\)</span> taking values in <span class="math inline">\(\mathbb R^2\)</span>. The independent variable of a parametric curve is called the parameter.</div>

Typically, the output of a parametric curve corresponding to input \$t\in I\$ is denoted by 
\$\$
    (x(t), y(t)). 
\$\$
\\begin{equation}
  \sin^2t + y^2 = 1
\\end{equation}


THis is a `.Rmarkdown` file. Outside of a fenced-in environment, I can not render math without escaping characters (use `/` to escape). For example `$\sin^2 \theta + \cos^2\theta = 1$` renders as `\(\sin^2 \theta + \cos^2\theta = 1\)` (both look like code), whereas `\$\sin^2 \theta + \cos^2\theta = 1\$` renders as \$\sin^2 \theta + \cos^2\theta = 1\$. 


<div class="example"><span class="example" id="exm:unnamed-chunk-2"><strong><span id="exm:unnamed-chunk-2"></span>Example 1  </strong></span>Perhaps the most familiar example of a parametric curve is the standard parameterization of the unit circle: <span class="math display">\[\begin{equation}
\label{eq:binom}
    (\cos t, \sin t) \qquad \text{ for } t\in [0, 2\pi)   
\end{equation}\]</span> This parameterization starts (when <span class="math inline">\(t = 0\)</span>) at the point <span class="math inline">\((0, 1)\)</span> and traverses the unit circle in the counter-clockwise direction. The circle is traversed exactly once and with constant speed.</div>



