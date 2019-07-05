======
Report
======


Capstone Project - The Battle of Neighborhoods
==============================================


Introduction
------------

This project is in fulfilment of the Applied Data Science Capstone [adsc]_ module offered by IBM
and hosted on Cousera.
The task is to think of an idea that leverages Foursquare [fsq]_ location data to explore or
compare neighborhoods or cities.
In this capstone project, we consider how someone can analyze the existing venues in a seaside town in England
in order to decide on the best place in which to open a new Fish & Chips shop.


Business Problem
----------------

There are **10,500** Fish & Chips shops in the UK, with an annual spend of **£1.2 billion** on fish and chips [nfff]_.
Bournemouth [brnm]_ was ranked as the number one most popular seaside resort of 2019
in the UK [indy]_.
Therefore, we want to open our new Fish & Chips shop in Bournemouth to capitalise on its popularity with a food shop
that is likely to be popular with the locals.

There are some considerations that we need to make when choosing where to open our new shop.
We want it to be in an area of the town where people would want to eat this kind of food.
That is, in an area that has lots of activities, such as drinking, shopping, and entertainment venues.
Preferably, such an area wouldn't already have many food venues, so that competition is as low as possible.


Data
----

To solve this task, we need to understand what venues are already in Bournemouth, so that we can analyse them and
decide on the best area in which to open our own shop.
We will use the venue recommendation API [expl]_ by Foursquare to gain insight into the recommended venues in Bournemouth.
We will then categorize these venues into six high-level groups:
Drink, Entertainment, Food, Hotel, Shopping, and Transport.

We will use these groups to understand how venues are dispersed by business type.
Then, we will use DBSCAN, a data clusting algorithm, to cluster venues based on their relative distance from each other.
This information will help us to determine where to open up our own Fish & Chips shop.


References
==========

.. [adsc] https://www.coursera.org/learn/applied-data-science-capstone
.. [brnm] https://www.bournemouth.co.uk
.. [expl] https://developer.foursquare.com/docs/api/venues/explore
.. [fsq] https://foursquare.com
.. [indy] https://www.independent.co.uk/travel/news-and-advice/uk-seaside-towns-beach-best-heatwave-summer-staycation-british-a8978111.html
.. [nfff] https://www.nfff.co.uk/pages/fish-and-chips
