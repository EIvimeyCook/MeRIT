---
layout: home
title: Homepage
---

<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>

<link href="css/ba-slider.css" rel="stylesheet" />
<script src="js/ba-slider.min.js"></script>

<div class="comparison-slider-wrapper">
    <div id="ba-slider" class="comparison-slider">
            <div class="overlay">text</div>
            <img src="MeRIT-new.png"/>
        <div class="resize">
            <div class="overlay">text</div>
            <img src="MeRIT-old.png"/>
        </div>
        <div class="divider"></div>
    </div>
</div>

<script>
    $(document).ready(function () {
        baSlider("#ba-slider");
    });
</script>
