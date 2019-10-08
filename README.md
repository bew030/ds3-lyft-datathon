# DS3 Datathon 2019 <img src="https://raw.githubusercontent.com/data-science-student-society/datathon2019/master/images/datathon.png" align="right" height="50">

_Created by Bernard Wong (bew030@ucsd.edu)_

Welcome to my DS3: Datathon repository! This repository contains all the [code and notebooks](https://github.com/bew030/ds3-lyft-datathon/tree/master/notebooks) that my team and written along with the [report](https://github.com/bew030/ds3-lyft-datathon/blob/master/writings/Lyft%20Paper.pdf) that we had submitted which had won the Datathon. This was my first datathon that I had participated in and it was a very rewarding experience and I look forward to participating in many other datathons in the future! 

Special thanks to the Data Science Student Society and all the sponsors for making this opportunity possible!

# Overview 

The Datathon provided us with 3 different datasets: one on Google Local Reviews, one on animal image classification, and one on traffic collisions in San Diego. The Datathon was very open ended, but the goal was to pick one dataset, perform an analysis, and extract insights (such as data visualization, hypothesis testing, classification models, etc.).

Our team decided to work with the traffic datasets, which included information on vehicle crashes and traffic levels that took place in San Diego. Our procedure included understanding and cleaning the datasets, brainstorming some questions that the data might answer, and utilizing visuals and statistics to help answer these questions and form a conclusion. 

To get more information about the organization of the Datathon, click [here](https://github.com/data-science-student-society/datathon2019). More information about the traffic dataset used can be found [here](https://github.com/data-science-student-society/datathon2019/tree/master/datasets/traffic). If you have any extra questions feel free to reach out by email or leave an issue. 

# An Overview on the Data 

# Using the Data to Answer Questions 

__What are some general patterns of traffic?__

As most of us have experienced, San Diego has its fair share of bad traffic. As a
big overview, we decided to first look at the traffic trends of San Diego over time. We
utilized an additional GeoDataFrame of roads that we downloaded and merged it with
the traffic dataset and then organized it by date. Afterwards, we created an animation of maps over time that would help give us a general idea of the trends of traffic:

<p align="center">
  <img src="https://github.com/bew030/ds3-lyft-datathon/blob/master/images/final_5d9bdd0264e738001470f299_973971.gif" />
</p>
<p align="center">
  <i> This is a naive timelapse of the routes that have the largest amount of traffic in San Diego. To view the video, click <a href="https://www.youtube.com/watch?v=j58cDTEEIx0&feature=youtu.be"> here </a> </i>
</p>

There are immediately some interesting things that you can notice from viewing
the animation. The general trend as time passes is that traffic becomes more and more
abundant as we start to notice more and more roads with traffic. We also noticed a few
sudden spurts of days where there is a lot of traffic covering all of California. This makes
sense, as traffic tends to create more traffic, and because there are many areas with
traffic during certain days, there’s a high chance that the traffic has an exponential effect.

This leads to more questions. There are random spurts of days where
there will be loads of traffic spread across all of California, and there are certain areas
where there are lots of traffic. Why is this? What are the days that have those spurts?
With this new development of questions, we continued to explore.

__What's the relationship between traffic and time?__
After finding the random spurts of traffic activity in the geographical data, we
wanted to find out if there was a correlation between the day of the week and the
amount of traffic. So using this data set, we plotted a histogram of the average amount of
cars per day of the week to see if the day of the week was a deciding factor towards why
there traffic was present.

# INSERT IMAGE HERE *


__What's the relationship between area and travel related injuries?__

# Further Analysis: A Pacific Beach Collision Case Study 

# What's Next? 

# Badges 
[![GitHub issues](https://img.shields.io/github/issues/bew030/ds3-lyft-datathon?color=purple)](https://github.com/bew030/ds3-lyft-datathon/issues)
[![GitHub forks](https://img.shields.io/github/forks/bew030/ds3-lyft-datathon?color=orange)](https://github.com/bew030/ds3-lyft-datathon/network)
[![GitHub stars](https://img.shields.io/github/stars/bew030/ds3-lyft-datathon)](https://github.com/bew030/ds3-lyft-datathon/stargazers)
[![Views](http://hits.dwyl.io/bew030/ds3-lyft-datathon.svg)](http://hits.dwyl.io/bew030/lyft-challenge)
