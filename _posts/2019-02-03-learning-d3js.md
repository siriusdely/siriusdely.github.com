---
title:  "Learning D3.js"
tags: [d3js, data visualization, javascript, learning]
---

I have been learning [**Machine Learning**](https://www.coursera.org/learn/machine-learning) for a few months. In the process, one hard-truth struck me well: **it needs data**.

Gathering data is usually a boring task, even when it is done in automated ways like **crawling and scraping**. When we've got the data crawled & scraped, there is a little chance that it is already in a good format. **Manual cleaning is still needed.**

However, this post is not about data gathering. Instead, I am going to talk about data visualization. I feel **visualizing data is much more interesting task**. So I decided to learn more about it.

There are many tools available to visualize our data, such as spreadsheet apps like [**MS Excel**](https://office.microsoft.com/en-us/excel) and [**Google Sheets**](https://sheets.google.com). Eventhough those tools are very powerful and widely used, **there are still limitations** compared to another tool that we are going to discuss.

Here comes a tool called [**D3.js**](https://d3js.org). It is a Javascript library for the web-browser for data visualization. In order to use it, one needs to understand Javascript, along with its companions: HTML & CSS. **The learning curve is steep. However, the gain is satisfying.** D3js is so much more powerful, flexible, and also make it possible for you to have interactivity within your visualization. Well, all of those benefits come from the platform D3js is intended for: web-browser.

You wouldn't fully appreciate the power of D3js until you see it with your own eyes by visiting its [**Gallery**](https://github.com/d3/d3/wiki/Gallery). In my opinion, its power is nearly limitless. One of the usage possibility that attracted me is **map visualization**. Using it for map visualization is a very modest usage of D3js. It makes map visualization task fairly easy, compared by using other tools, even if it is possible to do so.

My process of learning D3js is just a common way: finding good tutorials in the internet and follow it through. I think I have found **a list of good tutorials**. Here is the list:

1. [**Mapping with D3, a Friendly Introduction**](https://maptimeboston.github.io/d3-maptime), by Andy Wood for Maptime Boston.
2. [**D3 Workshop Series**](http://duspviz.mit.edu/d3-workshop) by DUSPViz of MIT
3. [**How to track down CPU issues in Node.js**](https://www.dynatrace.com/news/blog/how-to-track-down-cpu-issues-in-node-js) by Daniel Khan (wait, seriously?! Yes, it is!!!)

There is a [**Github repo I've made**](https://github.com/siriusdely/d3js) while following the tutorials. The repo is accompanied by [**helpful commit messages**](https://github.com/siriusdely/d3js/commits/master) point to related tutorial it is about. By looking at the commits, there are **also these two websites** keep being referenced: [**blocks (bl.ocks.org)**](https://bl.ocks.org) & [**Observable (beta.observablehq.com)**](https://beta.observablehq.com). Those are very cool websites for [**showcasing D3js work**](https://beta.observablehq.com/@mbostock). People are using it for hosting their D3js work for free. You can see [**D3js samples**](https://bl.ocks.org/mbostock) there with its following code, and of course you can showcase your work too.

Both sites are made by the [**Mike Bostock**](https://twitter.com/mbostock), the creator of D3js himself. I can see that Observable is a more modern one than blocks. While blocks is fetching code from [**Github Gist**](https://gist.github.com), Observable can be used for editing directly within it. Observable is more like [**Jupyter Notebook**](https://jupyter.org). I guess it is inspired by Jupyter Notebook, hence an instance of it is also called a notebook. I haven't tried both yet, probably later.

Lastly, back to the repo I've made, you can access it from [**https://siriusdely.com/d3js**](https://siriusdely.com/d3js). For instance, there is this [**projections.html**](https://github.com/siriusdely/d3js/blob/master/projections.html) inside the repo, it can be accessed directly on [**https://siriusdely.com/d3js/projections.html**](https://siriusdely.com/d3js/projections.html). Here is the look of it:
![projections.html](/assets/images/d3js-world-map-projection.jpg)
