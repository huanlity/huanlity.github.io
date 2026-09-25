---
layout: page
title: others
permalink: /others/
---

<style>
.photo-row {
  display: flex;
  gap: 8px;
  overflow-x: auto;
  padding-bottom: 8px;
}
.photo-row a {
  flex: 0 0 150px;
  width: 150px;
  height: 150px;
  display: block;
}
.photo-row img {
  width: 100%;
  height: 100%;
  display: block;
  border-radius: 4px;
  object-fit: cover;
}
.section-heading {
  font-size: 1.1rem;
  margin-bottom: 8px;
}
.section-heading a {
  color: #000;
  text-decoration: none;
}
</style>

<h2 class="section-heading"><a href="/others/ride/">ride</a></h2>
{% include photo-row.html category="ride" href="/others/ride/" %}

<h2 class="section-heading"><a href="/others/eat/">eat</a></h2>
{% include photo-row.html category="eat" href="/others/eat/" %}

<h2 class="section-heading"><a href="/others/kick/">kick</a></h2>
{% include photo-row.html category="kick" href="/others/kick/" %}
