---
theme: default
title: Time Series Forecasting
class: text-center
background: assets/stonks-bg.jpg
drawings:
  persist: false
transition: fade-out
mdc: true
---

# Time Series Forecasting

### Rishabh Wanjari

##### 20/06/2025

<!--
Before we begin, some **please** tell me they recognize this background so I feel validated.

Welcome to your introduction to time series forecasting! I'm going to be filling in for a collegue, as this isn't my area of expertise, but hopefully I can cover enough of the basics.

Let's start by talking about what a time series is, or rather, what it can be.
-->

---
transition: slide-up
---

# What is a time series?

<img class="mx-auto" width="700" src="./assets/cpu_usage.png">
<!--
Is this rainbow coloured atrocity a time series?
The x-axis isn't labelled, but it is. As the title says, it depicts CPU usage. While we're looking at the axes, what does it mean to use two thousand percent of your CPU? Is this a good representation of the data, or is there a better way? I will let you decide that.
-->


---
layout: center
transition: slide-left
---

<img class="mx-auto" width="500" src="./assets/fbk_internet.png">

<div v-click>
<tabler-arrow-left class="text-3xl text-red-400 mx-2 absolute top-31.5 left-146" />
<tabler-arrow-left class="text-3xl text-red-400 mx-2 absolute top-65.5 left-147" />
<tabler-arrow-left class="text-3xl text-red-400 mx-2 absolute top-103.5 left-146.5" />
</div>

<!--  -->

---
layout: default
src: ./pages/docker_logs.md
transition: slide-up
---

<!-- Is this time series data? It seems to have timestamps that correspond to values. It has some periodicity, has some outliers. Sure, right now, it isn't presented to you as a graph, but there's nothing stopping your from converting it to one. LLMs represent text as vectors, and vectors are just datapoints in higher dimensional spaces, so why not? -->

---
transition: slide-right
---

<img class="mx-auto" src="./assets/gitlab_stats.png">

---
transition: slide-up
---

<SlidevVideo class="mx-auto" width="500" controls>
  <source src="./assets/weather_android.mp4" type="video/mp4" />
  <p>
    Your browser does not support videos. :(
  </p>
</SlidevVideo>

---

<img class="mx-auto" width="500" src="./assets/windy.png">

---
layout: center
class: text-center
---

# Learn More

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />
