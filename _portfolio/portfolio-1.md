---
title: "Naive algorithmic collusion: when do bandit learners cooperate and when do they compete?"
excerpt: "Working paper"
collection: portfolio
---
_**Connor Douglas**, Foster Provost, Arun Sundararajan_

Abstract:

Algorithmic agents are used in a variety of competitive decision settings today, most notably to make
competitive pricing decisions in contexts that range from online retail to residential home rental. We study
the emergent behavior of competing agents using simple machine learning algorithms, when they are not
even aware they are engaged in strategic interaction. We use a general-form repeated Prisoner’s Dilemma
game as our model of strategic interaction. Agents engage in on-line learning with no prior model of game
structure, knowledge of competitors, or observation of competitors’ actions. Our primary question is: absent
any knowledge of the existence of the game or ability to pursue complex strategies like those that underlie
game-theoretic "folk theorems," when will agents nonetheless learn to collude?

We show that context-free bandits with no knowledge of their game environment and no time discounting
can still consistently learn collusive behavior, an outcome we call "naive collusion." Specifically, we prove that
all symmetric and deterministic bandit learning algorithms will always converge to a collusive equilibrium.
We further show that this finding is sensitive to the deterministic nature of these algorithms. In particular, we
also prove that particular families of non-deterministic algorithms—which include the textbook epsilon-greedy
algorithm—will never converge to a collusive equilibrium. Extensive simulations illustrate a range of outcomes
under varying levels of stochasticity in the bandit algorithms.