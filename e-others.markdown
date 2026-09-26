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
.post-content h2.section-heading {
  font-size: 26px;
  margin-bottom: 8px;
}
.section-heading a {
  color: #CB4335;
  text-decoration: none;
}
@media screen and (max-width: 800px) {
  .post-content h2.section-heading { font-size: 22px; }
}
</style>

<h2 class="section-heading"><a href="/others/ride/">ride</a></h2>
{% include photo-row.html category="ride" href="/others/ride/" %}

<h2 class="section-heading"><a href="/others/eat/">eat</a></h2>
{% include photo-row.html category="eat" href="/others/eat/" %}

<h2 class="section-heading"><a href="/others/kick/">kick</a></h2>
{% include photo-row.html category="kick" href="/others/kick/" %}
