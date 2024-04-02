---
layout: post
title:  "Narative Data story - Simon Urbak Pedersen & Albert Brincker Olson!"
date:   2024-04-02 11:43:53 +0100
categories: Assignment 2
---

<div class="container">
  <div class="column">
    <p>
      In this project we analyze the historical Police Incident Reports from DataSaf. This specific dataset is composed of all crimes in San Francisco in the years 2003 to May 2018. For this particular analysis we look specifically at the year 2017 and focus on the crimes of vehicle theft. The dataset has numerous attributes but in this project we are mainly interested in location, time and date of theft, as well as the type of vehicle stolen. The goal is to examine whether there is some pattern in what type of vehicles get stolen where and when. We divide the set of stolen vehicles into 3072 Automobile thefts, 1453 truck thefts, 602 Motorcycle thefts and 57 miscellaneous vehicle thefts. We hope that the analysis will show pattern for each vehicle, showing when and where to expect the highest risk of vehicle theft. We have divided the total into the sub categories because we are predisposed to believe that there will be some difference between them. The search for patterns are done only by data visualization.
    </p>
  </div>
  <div class="column">
    <p> First of all, we want to examine the distribution of vehicle theft over the year 2017. We do this with a calendar plot. This way we can see whether some months were particularly bad in regards to vehicle theft. Furthermore, a calendar plot can also give some pointers on whether any particular weekday has a higher risk of vehicle theft. 
From the calendar plots we notice a few patterns. First of all, we notice how the large categories; automobiles and trucks dominate the total number of stolen vehicles. For these two types, it seems that Friday and Saturday are the days with the highest risk of vehicle theft. Moreover, we see that the number of thefts are noticeably lower in November and December. Compared to trucks and automobiles, the motorcycle thefts look
more evenly distributed over all days of the week. Since there are far less stolen miscellaneous vehicles, it is hard to say anything about that particular calendar plot.
    </p>
  </div>
</div>

![Calendar Plots](/SIMON.jpg)

<div class="container">
  <div class="column">
    <p>
To gain insight into where the different vehicle types are stolen from, we plot the locations on a map of San Francisco, where the thefts are colored by vehicle types. The map is shown below. Upon inspection we see that overall, the 
    </p>
  </div>
  <div class="column">
    <p>
     downtown area to the north west is most common among the vehicle thefts. All the thefts the different vehicle types seem to be similarly distributed. The boundary of the dataset, i.e. the police precincts which are included. 
    </p>
  </div>
</div>

<iframe src="/ALBERT_SUTTER (1).html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="350"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

<div class="container">
  <div class="column">
    <p>  Another question that arises about the data is which times throughout the day are the vehicles stolen and does this differ from the different vehicle types? The graph below is constructed by counting stolen vehicles of each type within each hour of the day. Overall the thefts are most common between 16:00 to 24:00. 
    </p>
  </div>
  <div class="column">
    <p>
      There is also a noticeable spike at 12:00 - 13:00. This is possibly due to 12:00 being a default time for thefts where the time is not known. Looking at the individual vehicles, we see a similar pattern for each of them, with the exception of miscellaneous. This is most likely due to the low number of samples compared to the rest
    </p>
  </div>
</div>

<iframe src="/Luksus.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="350"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

Overall, the thefts of different vehicle types are quite similar in terms of their distribution in time and space. The only major difference is the number of occurrences, where automobiles are the most commonly stolen vehicle type, followed by trucks, motorcycles and miscellaneous. 

<style>
.container {
  display: flex;
}

.column {
  flex: 1;
  padding: 20px;
}
</style>




[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
