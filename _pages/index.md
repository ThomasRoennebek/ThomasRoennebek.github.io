---
layout: single
permalink: /
author_profile: false
classes: wide
---

## Introduction

Start with a **brief description of the dataset**, where it's from, and what your **main insight/storyline** is. Mention what you're trying to uncover about crime in San Francisco (e.g. trends, shifts, patterns).

---

## Crime Over Time

<figure>
  <img src="/assets/images/crime-over-time.png" alt="Crime Over Time">
  <figcaption><strong>Figure 1:</strong> Bar chart showing monthly/yearly crime counts by category.</figcaption>
</figure>

Include a short paragraph explaining **what this figure shows** — any rising/falling trends, surprises, or categories that changed drastically over time.

---

## Geospatial Distribution

<figure>
  <img src="/assets/images/crime-map.png" alt="Crime Map">
  <figcaption><strong>Figure 2:</strong> Map of San Francisco showing where crimes occurred most frequently.</figcaption>
</figure>

Use a static map (e.g. heatmap or dot map). Explain which neighborhoods stand out and how location correlates with crime types.

You can **mention `lat, lon`** points here or say something like:

> “As shown in the map, coordinates near the Mission District (lat: 37.7599, lon: -122.4148) had particularly high density of reported crimes.”

---

## Interactive Crime Explorer (Bokeh)

<div>
  <script src="/assets/interactive/bokeh-plot.js"></script>
</div>

<figcaption><strong>Figure 3:</strong> Interactive Bokeh visualization showing crime counts by time-of-day and category. Use dropdown menus to explore different filters.</figcaption>

Briefly describe what the user should look for. Does the data suggest crime happens more in the evening? Are some neighborhoods more active during certain times?

Make sure this is **not reused from Week 6**, or at least is based on **different data** or filters.

---

## Conclusion

Summarize your key findings, and restate the overall insight from your story. Mention what surprised you, and how this kind of data might help city officials or researchers.

---

## References

- [SF Crime Dataset](https://data.sfgov.org/)
- [Example: Mission Local News](https://missionlocal.org/)
- [Bokeh Docs](https://docs.bokeh.org/en/latest/)
