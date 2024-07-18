---
layout: page
title: BSc Thesis
description: with background image
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---

This project contains my BSc Thesis for Econometrics and Operational Research at the Erasmus University Rotterdam. The thesis is titled "Heterogeneity Analysis in Microcredit Financing: Application of Machine Learning Methods". The thesis is written in English and can be found by downloaded here: [BSc Thesis - Sem van Embden](assets/pdf/BSc_Thesis_final.pdf).

## Abstract
Microcredit financing has been shown to be a powerful tool for economic empowerment and poverty reduction. In this study, we use newly developed methods to analyze, estimate, and infer the heterogeneous effects in two randomized control trials (RCTs) conducted in Morocco and Bosnia and Herzegovina, where microcredit financing was introduced. By making use of key features such as the Best Linear Predictor (BLP), Group Average Treatment Effects (GATES), and Classification Analysis (CLAN), we estimate and interpret the varied treatment effects of microcredit on outcome variables related to e.g. outstanding credit, employment, and business outcomes. Using machine learning methods such as Random Forest and Boosting to estimate the Conditional Average Treatment Effect (CATE) I show that in Morocco, microcredit significantly increases the loan amount (p < 0.01) by 1, although the impact on output, profits and consumption is modest increasing by 5.2, 1.4 and -62 Moroccan Dhirams, respectively, and not statistically significant (p-values of 0.153, 0.486, and 0.425), with the significant heterogeneity in the amount of loans and profit (p < 0.1)
primarily driven by fixed effects present in the data rather than individual characteristics.
In Bosnia and Herzegovina, microcredit also shows varied impacts in outcome variables with most notably a significant increase in the amount of loans by 0.4 (p < 0.01), and decrease in savings by 456 Bosnian Marks (p < 0.1), yet the heterogeneity is less pronounced, only being close to significant for savings (p = 0.13). These findings highlight the importance of considering heterogeneous effects in microfinance program evaluations, suggesting that while
microcredit can aid economic development, its effectiveness may depend on targeting and contextual factors.

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

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
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
