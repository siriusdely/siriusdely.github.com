---
title:    "2014 Indonesian General Election Using D3.js"
author:   Sirius Dely
tags:     [javascript, d3js, data visualization, personal project, data crawling, portfolio]
---

[I have mentioned previously](https://siriusdely.com/learning-d3js) my primary reason to learn D3.js is for map visualization. I wanted to visualize the data of 2014 Indonesian General Election.

Indonesians are currently enthusiastic for the next 2019 General Election. It will be a rematch for the same presidential candidates. By providing a visualization of the result of the previous election, I hope each candidate and his team can make a campaign plan/strategy based on data.

After doing the tinkering, I come with a map of Indonesia with the regions colored according to which candidate who won. The map can be accessed at [**siriusdely.com/pilu**](https://siriusdely.com/pilu). One functionality available on the map is to choose the visualization based on provinces or districts/cities, as shown in the screenshots below:

![Winning Candidate by Provinces](/assets/images/pilu-winning-candidate-provinces.png)

![Winning Candidate by Regencies](/assets/images/pilu-winning-candidate-regencies.png)

The page is hosted and served through Github Page, which code is available at [**github.com/siriusdely/pilu**](https://github.com/siriusdely/pilu). The data is taken from the [**Indonesian General Election Commission's Official Site**](https://pilpres2014.kpu.go.id/dc1.php). There are two tools used to fetch the data: [**Cheeriojs**](https://cheerio.js.org) & [**Puppeteerjs**](https://pptr.dev). As both names imply, those two are Javascript packages, can be installed using the command: `npm install`.

Cheerio is what we use to get a specific element from the HTML three being shown on the web browser, much like [jQuery](https://jquery.com). While Puppeteer is what we use to drive the web browser to open a specific web page and perform certain actions on the page. Puppeteer is also usually used for web automated testing, as an alternative to [Selenium](https://docs.seleniumhq.org).

The working script can be seen [**here**](https://github.com/siriusdely/pilu/blob/master/scraper.js), which can be run by using the command: `node scraper.js`.

Below is the screenshot of other visualization pages available there:

![Margin Percentage of Winning Votes](/assets/images/pilu-winning-votes-margin-percentage.png)

![Amount of Voting Rights](/assets/images/pilu-votes-amount.png)

![Percentage of Unused Voting Rights](/assets/images/pilu-unvotes-percentage.png)
