[title: Sarah's Blog]:/
[menu: Home]:/

Sarah's Blog
===========

This is a test for Sarah's blog about low carb diets.

---

<div>
    <head_place>
         <script src="/js/jcarousellite_1.0.1.js" type="text/javascript"></script>
    </head_place>
    <button class="prev">prev</button>
    <div class="carousel" id="pictures">
    <ul data-lift="group?by=carousel">
      <li data-post="item"><img data-post="img" height="167" width="250" src="#"></li>
    </ul>
    </div>
    <button class="next">next</button>
    <script type="text/javascript">
    $(function() {
    $("#pictures").jCarouselLite({
       btnNext: ".next",
        btnPrev: ".prev"
    });
});</script>
</div>
---
<span data-lift="if?extra_true=has_blog">Here are my most recent blog posts:</span>

<div data-lift="if?extra_true=has_blog">
      <div data-lift="blog.simple"></div>
</div>

