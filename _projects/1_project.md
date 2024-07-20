---
layout: page
title: Selected Photos
description: Some Photos taken by Jason
img: assets/img/photos/Buddha Tooth Relic Temple.jpg
importance: 1
category: work
related_publications: false
---

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width. -->

<!-- To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/photos/Buddha Tooth Relic Temple.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Buddha Tooth Relic Temple, SGP
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <figure>
            {% include figure.liquid loading="eager" path="assets/img/photos/DSC_2353.jpg" class="img-fluid rounded z-depth-1" %}
            <figcaption class="text-center">Gradens by the Bay, SGP</figcaption>
        </figure>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <figure>
            {% include figure.liquid loading="eager" path="assets/img/photos/Jurong East.jpg" class="img-fluid rounded z-depth-1" %}
            <figcaption class="text-center">Jurong East, SGP</figcaption>
        </figure>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <figure>
            {% include figure.liquid loading="eager" path="assets/img/photos/DSC_3336.jpg" class="img-fluid rounded z-depth-1" %}
            <figcaption class="text-center">Merese Hill, Lombok, IDN</figcaption>
        </figure>
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <figure>
            {% include figure.liquid loading="eager" path="assets/img/photos/DSC_1359.jpg" class="img-fluid rounded z-depth-1" %}
            <figcaption class="text-center">Orangutan, SGP</figcaption>
        </figure>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <figure>
            {% include figure.liquid loading="eager" path="assets/img/photos/DSC_2024.jpg" class="img-fluid rounded z-depth-1" %}
            <figcaption class="text-center">Flamingo, SGP</figcaption>
        </figure>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <figure>
            {% include figure.liquid loading="eager" path="assets/img/photos/Cat_Liaoning.jpg" class="img-fluid rounded z-depth-1" %}
            <figcaption class="text-center">Dragon Li, Liaoning, CHN</figcaption>
        </figure>
    </div>
</div>
<!-- <div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div> -->


<!-- You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images. -->

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
    <figure>
        {% include figure.liquid path="assets/img/photos/Penang1.jpg" class="img-fluid rounded z-depth-1" %}
        <figcaption class="text-center">Little India, Penang, MYS</figcaption>
    </figure>
    </div>
    <div class="col-sm mt-3 mt-md-0">
    <figure>
        {% include figure.liquid path="assets/img/photos/BukitBendera.jpg" class="img-fluid rounded z-depth-1" %}
        <figcaption class="text-center">Bukit Bendera, Penang, MYS</figcaption>
    </figure>
    </div>
    <div class="col-sm mt-3 mt-md-0">
    <figure>
        {% include figure.liquid path="assets/img/photos/SultanMosque.jpg" class="img-fluid rounded z-depth-1" %}
        <figcaption class="text-center">Sultan Mosque, SGP</figcaption>
    </figure>
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
    <figure>
        {% include figure.liquid path="assets/img/photos/Merese Lombok.jpg" class="img-fluid rounded z-depth-1" %}
        <figcaption class="text-center">Merese Hill, Lombok, IDN</figcaption>
    </figure>
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
    <figure>
        {% include figure.liquid path="assets/img/photos/Harvest.jpg" class="img-fluid rounded z-depth-1" %}
        <figcaption class="text-center">Paddy Field, Liaoning, CHN</figcaption>
    </figure>
    </div>
</div>

<!-- <div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div> -->

<!-- The code is simple.
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

{% endraw %} -->
