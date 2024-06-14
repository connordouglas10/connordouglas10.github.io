---
title: "Computing an Optimal Pitching Strategy in a Baseball At-Bat"
excerpt: "Proceedings of FLAIRS-36 Conference (2023)"
collection: portfolio
---

_**Connor Douglas**, Everett Witt, Mia Bendy, Yevgeniy Vorobeychik_

Abstract:

The field of quantitative analytics has transformed the world
of sports over the last decade. To date, these analytic ap-
proaches are statistical at their core, characterizing what is
and what was, while using this information to drive decisions
about what to do in the future. However, as we often view
team sports, such as soccer, hockey, and baseball, as pairwise
win-lose encounters, it seems natural to model these as zero-
sum games. We propose such a model for a baseball at-bat,
which is a matchup between a pitcher and a batter. Specifi-
cally, we propose a novel model of this encounter as a zero-
sum stochastic game, in which the goal of the batter is to get
on base, an outcome the pitcher aims to prevent. The value
of this game is the on-base percentage (i.e., the probability
that the batter gets on base). In principle, this stochastic game
can be solved using classical approaches. The main techni-
cal challenges lie in predicting the distribution of pitch loca-
tions as a function of pitcher intention, predicting the distri-
bution of outcomes if the batter decides to swing at a pitch,
and characterizing the level of patience of a particular batter.
We address these challenges by proposing novel pitcher and
batter representations as well as a novel deep neural network
architecture for outcome prediction. Our experiments using
Kaggle data from the 2015 to 2018 Major League Baseball
seasons demonstrate the efficacy of the proposed approach.