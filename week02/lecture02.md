---
title: A few notes about data types
layout: lecture
---

<img src="https://static.wixstatic.com/media/6efa5f_e6f70adbf18e41fd8e369abc4c309563~mv2.png/v1/fill/w_770,h_434,al_c,lg_1,q_85/Types%20of%20Data_Visual_PNG.webp">

notes:
So, usually you're probably used to thinking about data like this - numerical or quantitative which is then broken down into discrete & continous.

Also categorical or qualitative data which is either ordered (ordinal) or unordered (nominal).

---

<img src="https://static.wixstatic.com/media/6efa5f_e6f70adbf18e41fd8e369abc4c309563~mv2.png/v1/fill/w_770,h_434,al_c,lg_1,q_85/Types%20of%20Data_Visual_PNG.webp">

We need to dig a little deeper for visualizing data.

notes:
This is a fine for something like stats, but we have to start thinking about how data type and format maps itself visually -- what is the best mapping for our visual cortex?

---

### Data organization is important

<div class="left">
	<img src="images/tamaraSlide.png" width=450>
</div>
<div class="right">
    <img src="images/tamaraTables.png" width=350>
	 - Munzner - https://www.cs.ubc.ca/~tmm/talks.html

</div>



notes:
We have to think a little bit about how our data represents reality *and* how it is represented on disk.

for example, both spatial data like that on a map and data that we use to compare salaries for example, are numerical data - we have lat/long and data value combinations for geographic data and numbers for salaries, but there is something fundementally different about how we would represent these two datasets on a visualization

Similarly for categorical data like with an organization, network, or a tree -- this data is much different than a table of categorical occurances.

---

### Example: Temporal data is numerical, but its also something "else"

<!-- .slide: class="two-floating-elements" -->

<div class="left">

<img src="https://clauswilke.com/dataviz/aesthetic_mapping_files/figure-html/temp-normals-vs-time-1.png" width="400px">

</div>

<div class="right">

<img src="https://clauswilke.com/dataviz/coordinate_systems_axes_files/figure-html/temperature-normals-polar-1.png" width="400px">

</div>

notes:
temporal data, like here the temperature change in a vew places over time, is numerical, but, depending on what time spans we are interested in, its can also be periodic

The first graph tell us a lot, and the 2nd may at first be a little weird to read but it tells us information about both changes in time and the averages about the place *and* it captures a central nature about this data - that it is periodic

---
