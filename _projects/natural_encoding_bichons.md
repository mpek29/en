---
layout: page
title: Bichons
description: Image synthesis in Python
img: assets/img/projects/natural_encoding_bichons/main.jpg
importance: 5
category: 2022
---

During my 4th semester at ENIB, as part of the subject dedicated to Euclidean space, and following on from the "Sound recognition" project that you can find on this site, my colleagues and I had the opportunity to work on a project using a "bichon" database (a set of dog and cat photos). With this base, we had to create a "synthetic" image from a selected original image.

To do this, we expressed our image in a Euclidean space with the "bichon" 's base , which was previously rendered orthonormal. This was made possible by using the scalar product associated with the space in question to project the photo to be synthesized onto the base.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/natural_encoding_bichons/main.jpg" class="img-fluid rounded z-depth-1" caption="Original image" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/img/projects/natural_encoding_bichons/1.jpg" class="img-fluid rounded z-depth-1" caption="Image synthesis using 200 bichons" %}
    </div>
</div>
