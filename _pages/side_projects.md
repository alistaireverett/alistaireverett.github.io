---
title: Side Projects
permalink: /side_projects/
---

Below is an overview of some side projects, tinkerings, and parts of larger projects which I've been working on. Some are finished, some are half-finished, and some are a complete mess. A lot of them were learning experiences, and so the coding and style probably isn't perfect. I've tried to make as much of the code available as possible, get in touch if there's something you're interested in that I haven't made available.

## Live-update an interactive map from your satphone
<figure>
  <a href="/assets/images/demolivemap.jpg"><img src="/assets/images/demolivemap.jpg"></a>
</figure>
This was written to use while we were on an expedition in Greenland, so that we could update people interested in following our expedition. We had a satphone but didn't want to purchase an InReach or something similar in addition. So we wrote this app instead. The code achieved that and also made the interactive map a bit more customisable than with an InReach, for example you can select custom symbols to display from a library set up in advance. If you're interested in using this go ahead and fork the repo or get in touch if you need help setting it up.

Demo: [https://demolivemap.herokuapp.com/](https://demolivemap.herokuapp.com/){:target="_blank"}

Code: [https://github.com/alistaireverett/livemap]( https://github.com/alistaireverett/livemap){:target="_blank"}

## Interactive climate data portal
<figure>
  <a href="/assets/images/climate_interactive.jpg"><img src="/assets/images/climate_interactive.jpg"></a>
</figure>
Experimenting with d3.js to set up a website which pulls historical climate data from met office APIs and plots it nicely. The "climate stripes" plots were inspired by [Ed Hawkins/Climate Lab Book](https://www.climate-lab-book.ac.uk/2018/warming-stripes/){:target="_blank"}. I've started off with Met.no's [Frost API](https://frost.met.no){:target="_blank"}, since they make a lot of data easily accessible. The idea is that any weather station with a long enough record should be available, and that there should be a number of different ways of plotting the data. All of this should be simple, and the plots should be clear and easy to interpret, keeping the data as close as possible to the raw weather station data.

Demo: [https://climateinteractive.herokuapp.com/](https://climateinteractive.herokuapp.com/){:target="_blank"}

Code: [https://github.com/alistaireverett/climatedata](https://github.com/alistaireverett/climatedata){:target="_blank"}

## Stauning Alps mapping
<figure>
  <a href="/assets/images/stauning_map.png"><img src="/assets/images/stauning_map.png"></a>
</figure>Very little mapping data is available for the Stauning Alps. The best is at a scale of 1:250,000. In addition, a lot of the features on the ground which we were interested in avoiding (eg. crevasses and meltwater streams), wouldn't be marked on the maps anyway. These days, satellite imagery is available at an incredibly high resolution, we were lucky to be successful in an application to the [Digital Globe Foundation](http://foundation.digitalglobe.com/){:target="_blank"}, who provided us with 0.5 metre resolution imagery over the year preceding our expedition. From this I was able to map meltwater streams and crevasses, which in winter might be covered by thin snow bridges. I also included potential safe routes through danger areas, the easiest ways through complex moraines and lines to take when ascending and descending from col crossings. In this end this information proved incredibly valuable and saved us time navigating melt streams and avoiding unnecessary crossings of streams and crevasse fields. I am happy to share these maps, please get in touch if you are interested (but beware: some features and locations may now be out of date).
