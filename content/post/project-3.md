---
date: 2020-08-02T11:00:59-04:00
description: ""
featured_image: ""
tags: []
title: "Top 10 defensive players of Superliga in season 2019/20"
---

Looking at the defensive facet of the game is not an easy approach using metrics. Firstly, teams that have more the ball will have fewer defensive actions per game. Therefore, all defensive metrics must be adjusted by the possession of the team. Secondly, there are not many metrics at the current moment that describe the way teams defend.  

Nevertheless, it is known that the best way to adjust defensive actions by possession is by applying the effective time possession of each team. This is the time each team was in possession of the ball discounting every interruption the game had. Sadly, this metric is not open to the public.

From a StatsBomb article I found my solution (link below). Basically, using the average possession percentage of each squad, I applied a Sigmoid function to calculate the tackles and interception actions adjusted by possession. 

Looking at the viz, the player that singles out by far, is Adrián Cubas. He has more than 9 defensive actions per game. He is a bargain, and that is why he is going back to Europe to play the next season.

{{< figure src="/images/defensive.png" title="" >}}

[Link to StatsBomb Article](https://statsbomb.com/2014/06/introducing-possession-adjusted-player-stats/”)

[Link to Github Repository](https://github.com/rcammi/DefAttributesSuperliga)