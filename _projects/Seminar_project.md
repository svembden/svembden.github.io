---
layout: page
title: Seminar Paper
description: a project with a background image and giscus comments
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

This project contains my the paper written for for the Seminar for Econometrics and Operational Research at the Erasmus University Rotterdam. The paper is titled "Is your neighbour’s balcony cheaper than yours?: Investigating the effect of incorporating geographical data on the predictive performance of hedonic pricing models in Rotterdam’s rental property market" and is written in English. This paper is co-written with Willem Amesz, Anna Grefhorst and Wenske Tuk. The pdf can be downloadeded here: [Seminar Paper](assets/pdf/Final_Report__ML_.pdf).

## Abstract
A common problem in the housing market is the accurate valuation of properties, considering the multitude of attributes that influence prices. This paper considers traditional hedonic pricing models, such as Ordinary Least Squares with forward selection, Least Absolute Shrinkage and Selection Operator (LASSO) and the popular Random Forest model, as well as their geographically weighted counterparts. Specifically, we focus on a Geographically Weighted Regression (GWR) and a Geographically Weighted Random Forest (GWRF), evaluating their comparable predictive performance in the context of the rental housing market in Rotterdam. Using a unique dataset including wardspecific characteristics, we aim to assess the effect of incorporating geographical data into traditional pricing models. Through empirical analysis and comparison of predictive performance metrics, we provide insights into the strengths and limitations of these approaches. We find there is an improvement in predictive power in the use of the Geographically Weighted Regression over the standard
Ordinary Least Squares method, but no substantial improvement in the use of a Geographically Weighted Random Forest versus a standard Random Forest model in the city of Rotterdam. Finally, this paper uses Partial Dependence, LIME, and ALE methods to interpret the Random Forest model and finds there are different preferences for features per ward in Rotterdam.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
