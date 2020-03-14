---
layout: layouts/post2.njk
title:
tags:
  - nav
navtitle: About
templateClass: tmpl-post
---

<style>
.about-page a {
  color: var(--primary-color);
  font-weight: 700;
}
</style>

I'm going to put a few things in here - stuff I'm learning (aka trying to figure out)

## How many stars does eleventyjs have as of today?
<p id="date"></p>

### {{ github.stargazers }} GitHub Stars


<script>
{
  var d = new Date();
  var n = d.toDateString();
  document.getElementById("date").innerHTML = n;
}
</script>