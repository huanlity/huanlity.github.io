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
</style>

<h2><a href="/others/ride/">ride</a></h2>
{% include photo-row.html folder="/asset/ride/" href="/others/ride/" %}

<h2><a href="/others/eat/">eat</a></h2>
{% include photo-row.html folder="/asset/eat/" href="/others/eat/" %}

<h2><a href="/others/kick/">kick</a></h2>
{% include photo-row.html folder="/asset/kick/" href="/others/kick/" %}
