---
layout: postWithoutDate
title:  "5 Game Theory"
date:   2020-05-31
permalink: "/Game-Theory/"
---
  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript" ></script>
  
In competitive markets firms have no incentives to think about what a specific competitor is doing. The reason is that their profits depend on the market price and none of the other firms can unilaterally affect it ---they are too small to do so. In this type of environment, there is no no room for strategic thinking. However, there are many other economic contexts, in which strategic thinking plays a fundamental role. As an example, recall our oligopoly analysis.

In this section we will study situations in which the payoff of each agent depends on the actions of others. We refer to these situations as games. Moreover, we will focus on static games.

In a static game, players act simultaneously and only once. We assume that each player knows how everyone’s actions translate into payoffs, but cannot observe the choices of others.

We next present different examples of games and discuss their main features.

**Prisoner's Dilemma / Social Dilemma**

Imagine the following situation. Adam likes to watch a tv show online but dislikes online advertisement; so, he is contemplating the possibility of installing an ad blocker in his browser. Suppose he knows that there are only two people in the country that like this show. The other person (let’s call her Bob) is probably considering the same decision.

But this is where it gets interesting. The website is funded by ads. Thus, if both players block ads the website cannot operate. Let’s say, A and B in such a situation get a utility of 0. If, instead, only A installs an ad blocker, then he gets a utility of 2 and the one without the blocker gets to watch a lot of adverts and gets a utility of -1. If only B installs the adblocker, B gets 2 and A gets -1. If none of them installs the ad blocker, so they both get to watch the show and need to bear some ads, they both receive a utility of 1. All this information can be summarized in the so-called bi-matrix.

<img src="{{ site.baseurl }}/img/gametheory/GTAdBlocker.PNG">

The question we are interested in is: 

$$What\; will\; Adam\; and\; Bob\; do?$$ 

To answer this question, we start by asking what should player A do if he believes B will take a specific action. 

Suppose A thinks B is installing the Ad Blocker. In that case, he gets a payoff of zero by installing the ad blocker or a payoff of -1 by not installing the ad blocker. Thus, he should also install the ad blocker.  

Similarly, if A believes that B will not install the  ab blocker, then he gets a payoff of 2 by installing the ad blocker or a payoff of 1 by not installing it. Again, B is better off installing the ad blocker. 

Since for A it is always better to install the ad blocker regardless of what Bob will do, we say that “installing” is a dominant strategy for him. 

Repeating the exercise for B, we find that “installing” is also a dominant strategy for this person. 

The logical conclusion is therefore that they will both follow their dominant strategies and install the ad blocker. Doing so, they will each end up with a payoff of 2. 

Because in this case both players are choosing their dominant strategies, we call this type of outcome an equilibrium in dominant strategies. 

An interesting observation is that ---in this example--- they could both end up better off by cooperating and choosing not to install the ad blocker. However, by following their dominant strategy then end up a lower payoff situation. We call this type of situation a “social dilemma” or a “prisoner’s dilemma game”.

**Coordination Game / Battle of the Sexes**

Another standard model in game theory is the so-called coordination game. In this situation, the incentives of the players are aligned but there are multiple possible outcomes to coordinate on. The classic example of this type of game is the “battle of the sexes”. 

In the battle of the sexes, each member of a married couple has to decide where to go during the weekend. There are two options, each of them can either go to see boxing or ballet. While both prefer to coordinate in one of these options, their preferences regarding the best option differ. 
The wife prefers going to see ballet together (payoff of 2) over boxing together (payoff of 1), which in turn is preferred to either option by herself (payoff of 0). The husband prefers going to see boxing together (payoff of 2) over ballet together (payoff of 1), which in turn is preferred to either option by himself (payoff of 0). As you can see, the interdependence in this situation is quite clear: If one of the partners goes to a specific place, then the other one prefers to go to that place too. 

In this situation, it is hard to predict what the couple will do. In particular, there two likely outcomes or equilibria. The first equilibrium is going together to see ballet; this outcome is an equilibrium because when each member of the couple thinks the other one will do so, it is in his/her interest to go to the ballet. Using a similar argument, we can show that going to see boxing is also an equilibrium. The following table illustrates this situation. 

<img src="{{ site.baseurl }}/img/gametheory/GTBotS.PNG">

The important takeaways from this example are: 1) strategic interdependence implies that my best strategy might change with what I think “the other” will do; 2) there can be more than one equilibrium; and 3) not all games have dominant strategies. 

The equilibria for this game is not one in dominant strategies. Instead, each equilibrium (ballet, ballet) and (boxing, boxing) is simply an equilibrium in best responses. This type of equilibrium is known as Nash Equilibrium and is due to the famous mathematician [John Nash](https://en.wikipedia.org/wiki/John_Forbes_Nash_Jr.).

Mixed Strategies
In the previous two games, there was at least one equilibrium in which each player implemented a strategy with certainty. For example, when we say that (ballet, ballet) is an equilibrium we mean that the wife chooses ballet for sure and husband chooses ballet for sure as well. We refer to this type of equilibrium as pure-strategy equilibrium. Unfortunately, many games do not have an equilibrium in pure-strategies. In these cases, we often use mixed strategy equilibria as our solution concept. 
 
Let’s illustrate the concept of mixed strategy equilibrium with one example. Imagine a penalty kick situation, where player A is the kicker and player B is the goal keeper. To make things simple, let us assume that the kicker has to decide whether to kick left or right. As a consequence, the goalkeeper has to choose whether to fly right or to fly left. Also, let us assume that if the kick goes to the same side that the keeper jumps to, then there is no score and payoffs are 0 for the kicker and 1 for the keeper. If, on the other hand, the kick and the keeper jump to different sides, we assume there is a score and payoffs are 1 for the kicker and 0 for the keeper. The following table illustrates this game.

<img src="{{ site.baseurl }}/img/gametheory/GTsoccer.PNG">

Because the kicker wants to choose a different side than keeper, and the keeper wants to choose the same side as kicker, there is no equilibrium in pure strategies. To see this more clearly, imagine, for example, that the kicker believes the goalkeeper is going to the left. In this case, he will want to kick to the right. But if the keeper believes the kick is coming to the right, the keeper will want to deviate and fly to the right, instead. 

However, we can find here an equilibrium in mixed strategies. It consists of ,In our example, the kicker will randomly select left or right with 50% chance each, so the kicker cannot guess what he will do. Conversely, the goalkeeper will fly to the right or the left with a 50% chance each. 

