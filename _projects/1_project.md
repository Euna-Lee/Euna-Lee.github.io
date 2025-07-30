---
layout: page
title: Super Food Chain
description: A action snake-like game where you assemble a chain of flavorful allies in a battle against enemies for culinary domination.
img: assets/img/SuperFoodChain.png
importance: 1
category: work
related_publications: true
---

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->

A link to the downloading and finding more about the game is here: <a href="https://gdiac.cs.cornell.edu/gdiac/showcase/gallery/superfoodchain/">Super Food Chain</a>.

This project was a challenge because it was the first large-scale game I created with a team mixed of programmers and artists. There were interesting problems we encountered that I never considered beforehand such as the artists not sharing the programmers' vision which created a disconnect in what was needed. Additionally, since most of the features were so entwined, we had to work closely and explain our code to each other often despite trying to split up the work. I mainly worked on the collisions of this game which was a learninge experience in itself because I had to learn to use the LibGDX Box2D libraries to get the desired results. It was very confusing to work with and caused many distruptive bugs that took hours of toil to figure out and fix but the end result was worth it. Another interesting challenge was balancing since we had a small pool of those willing to playtest our game that were either too good or too bad at playing. We eventually modified the gameplay to be much easier than we had originally intended but it matched the target audience of our game showcase which were 10-15 year olds.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_1.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_2.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_3.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    These pictures show captures of gameplay against each of the 3 bosses available: The Rat, Chopsticks, and Chef.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_4.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_5.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The left picture is the journal that updates as you encounter new companions and enemies. The right picture is the level select that unlocks the next level once you beat the previous one.
</div>

<!-- <div class="row justify-content-sm-center">
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
``` -->

{% endraw %}
