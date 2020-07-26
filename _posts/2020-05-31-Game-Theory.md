---
layout: postWithoutDate
title:  "5 Game Theory"
date:   2020-05-31
permalink: "/Game-Theory/"
---
  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript" ></script>

In competitive markets firms have no incentives to think about what a specific competitor is doing. The reason is that their profits depend on the market price and none of the other firms can unilaterally affect it--they are too small to do so. In this type of environment, there is no room for strategic thinking. However, there are many other economic contexts, in which strategic thinking plays a fundamental role. As an example, recall our analysis of an oligopoly market.

In this section we will study situations in which the payoff of each agent depends on the actions of others. We refer to these situations as games. In Game theory there are two types of games:

* Static Games: Each player acts simultaneously and only once.  We assume that each player knows how everyone’s actions translate into payoffs, but cannot observe the choices of others.

* Dynamic Games: Players act sequentially. It is assumed that each player has a perfect recollection of what happened prior to his/her turn to decide.

We will first focus on intuition of Statics games along with the mathematics involved in these games. Afterward we explore the key concepts of Dynamic games

**Prisoner's Dilemma / Social Dilemma**

Imagine the following situation. Adam likes to watch a tv show online but dislikes online advertisement; so, he is contemplating the possibility of installing an ad blocker in his browser. Suppose he knows that there are only two people in the country that like this show. The other person (let’s call her Bob) is probably considering the same decision.

But this is where it gets interesting. The website is funded by ads. Thus, if both players block ads the website cannot operate. Let’s say, A and B in such a situation get a utility of 0. If, instead, only A installs an ad blocker, then he gets a utility of 2 and the one without the blocker gets to watch a lot of adverts and gets a utility of -1. If only B installs the adblocker, B gets 2 and A gets -1. If none of them installs the ad blocker, so they both get to watch the show and need to bear some ads, they both receive a utility of 1. All this information can be summarized in the so-called bi-matrix.

<img src="{{ site.baseurl }}/img/gametheory/GTAdBlocker.PNG">

The question we are interested in is:

$$What\; will\; Adam\; and\; Bob\; do?$$

To answer this question, we start by asking what should player A do if he believes B will take a specific action.

Suppose A thinks B is installing the Ad Blocker. In that case, he gets a payoff of zero by installing the ad blocker or a payoff of -1 by not installing the ad blocker. Thus, he should also install the ad blocker.  

Similarly, if A believes that B will not install the ad blocker, then he gets a payoff of 2 by installing the ad blocker or a payoff of 1 by not installing it. Again, B is better off installing the ad blocker.

Since for A it is always better to install the ad blocker regardless of what Bob will do, we say that “installing” is a dominant strategy for him.

Repeating the exercise for B, we find that “installing” is also a dominant strategy for person B.

We say that a strategy s is a dominant strategy if it produces a higher payoff than other strategies regardless of rivals’ strategies. In other words, if a player has an optimal strategy irrespective of the other player's move, such a strategy is the "dominant strategy".

Therefore The logical conclusion for Player A and Player B is that they will both follow their dominant strategies and install the ad blocker. Doing so, they will each end up with a payoff of 2.

Because in this case both players are choosing their dominant strategies, we call this type of outcome an equilibrium in dominant strategies.

An interesting observation is that ---in this example--- they could both end up better off by cooperating and choosing not to install the ad blocker. However, by following their dominant strategy then end up a lower payoff situation. We call this type of situation a “social dilemma” or a “prisoner’s dilemma game”.


**Coordination Game / Battle of the Sexes**

Another standard model in game theory is the so-called coordination game. In this situation, the incentives of the players are aligned but there are multiple possible outcomes to coordinate on. The classic example of this type of game is the “battle of the sexes”.

In the battle of the sexes, each member of a married couple has to decide where to go during the weekend. There are two options, each of them can either go to see boxing or ballet. While both prefer to coordinate in one of these options, their preferences regarding the best option differ.

The wife prefers going to see ballet together (payoff of 2) over boxing together (payoff of 1), which in turn is preferred to either option by herself (payoff of 0). The husband prefers going to see boxing together (payoff of 2) over ballet together (payoff of 1), which in turn is preferred to either option by himself (payoff of 0). As you can see, the interdependence in this situation is quite clear: If one of the partners goes to a specific place, then the other one prefers to go to that place too.

In this situation, it is hard to predict what the couple will do. In particular, there two likely outcomes or equilibria. The first equilibrium is going together to see ballet; this outcome is an equilibrium because when each member of the couple thinks the other one will do so, it is in his/her interest to go to the ballet. Using a similar argument, we can show that going to see boxing is also an equilibrium. The following table illustrates this situation.

<img src="{{ site.baseurl }}/img/gametheory/GTBotS.PNG">

The important takeaways from this example are:

1. Strategic interdependence implies that one's best strategy might change with what they think “the other” will do

2. There can be more than one equilibrium

3. Not all games have dominant strategies.

The equilibria for this game is not one in dominant strategies. Instead, each equilibrium (ballet, ballet) and (boxing, boxing) is simply an equilibrium in best responses. This type of equilibrium is known as Nash Equilibrium and is due to the famous mathematician [John Nash](https://en.wikipedia.org/wiki/John_Forbes_Nash_Jr.).

Two great example that we have already seen is the Cournot Duopoly and the Bertrand Duopoly from Chapter 4.


**Mixed Strategies**

In the previous two games, there was at least one equilibrium in which each player implemented a strategy with certainty. For example, in The Battle of The Sexes when we say that (ballet, ballet) is an equilibrium we mean that the wife chooses ballet for sure and husband chooses ballet for sure as well. We refer to this type of equilibrium as pure-strategy equilibrium. Unfortunately, many games do not have an equilibrium in pure-strategies. In these cases, we often use mixed strategy equilibria as our solution concept. Practically speaking mixed strategy equilibria are seen in a vast variety of games--some examples are:

1. Tennis Service
2. Poker
3. Warfare
4. Penalty Kick in Soccer


Let’s illustrate the concept of mixed strategy equilibrium by exploring the last example. Imagine a penalty kick situation, where player A is the kicker and player B is the goal keeper. To make things simple, let us assume that the kicker has to decide whether to kick left or right. As a consequence, the goalkeeper has to choose whether to dive right or to dive left. Also, let us assume that if the kick goes to the same side that the keeper jumps to, then there is no score and payoffs are 0 for the kicker and 1 for the keeper. If, on the other hand, the kick and the keeper jump to different sides, we assume there is a score and payoffs are 1 for the kicker and 0 for the keeper. The following table illustrates this game.

<img src="{{ site.baseurl }}/img/gametheory/GTsoccer.PNG">

Because the kicker wants to choose a different side than keeper, and the keeper wants to choose the same side as kicker, there is no equilibrium in pure strategies. To see this more clearly, imagine, for example, that the kicker believes the goalkeeper is going to the left. In this case, he will want to kick to the right. But if the keeper believes the kick is coming to the right, the keeper will want to deviate and dive to the right, instead.

However, we can find here an equilibrium in mixed strategies. It consists of, in our example, the kicker will randomly select to kick left or right with 50% chance each, so the goalkeeper cannot guess what he will do. Conversely, the goalkeeper will dive to the right or the left with a 50% chance each.

**Solving the Equilibria**

Up until now we have described some important concepts in game theory--such as equilibrium of best responses--pertaining to Static games and we have illustrated them with examples of different static games. Now we wish to build upon this conceptual foundation by utilizing an analytical tool, the best response curve, to help us solve for the equilibria in a game.

Let's consider a general game between two players--Player Row and Player Column. Player Row has the choices $$r_1,..., r_R$$ and Player Column has the choices $$c_1,..., c_C$$. For each choice $$r$$ that Player Row makes, let $$b_c(r)$$ be the best response Player Column makes, likewise for each choice $$c$$ that Player Column makes, let $$b_r(c)$$ be the best response Player Row makes. Then the Nash Equilibrium is a pair of strategies $$(r^* , c^* )$$ such that

$$c^* =b_c(r^* )$$

$$r^* =b_r(c^* )$$

By deriving the Nash Equilibrium this way we formulize the idea of “mutual consistency.” If row expects column to play left, then row will choose to play top, and if column expects row to play top, column will want to play left. So it is the beliefs and the actions of the players that are mutually consistent in a Nash equilibrium.

Note that in some cases one of the players may be indifferent among several best responses. This is why we only require that $$c^* $$ be one of the column's best responses, and $$r^* $$ be one of row’s best responses. If there is a unique best response for each choice then the best response *curves* can be represented as best response *functions*.


<img src="{{ site.baseurl }}/img/gametheory/Fig30.2.PNG">

First we start by letting $$r$$ be the probability that Mr. Row plays Top, and let $$(1-r)$$ be the probability that he plays bottom. Likewise, let $$c$$ be the probability that Mr. Column plays Left, and let $$(1-c)$$ be the probability that he plays right.

Before we move forward note that the equilibria is a pure strategy equilibria if and only if $$r$$ and $$c$$ equal 0 or 1. Otherwise we have $$0<r,c<1$$ indicating a mixed strategy equilibria.

We can use the following table to help us calculate the expected payoff of Mr. Row and Mr. Column


Combination  | Probability | Mr.R's Payout | Mr.C's Payout
:-----------:|:-----------:|:-------------:|:-------------:
Top, Left    | rc          |  2            |  1
Bottom, Left | (1-r)c      |  0            |  0
Top, Right   | r(1-c)      |  0            |  0    
Bottom, Right| (1-r)(1-c)  |  1            |  2


To calculate the expected payoff to Mr.Row, we weight Mr. Row’s payoffs in the third column by the probability that they occur, given in the second column, and add these up. The payoff for Mr. Row becomes

$$\pi_{row} (r,c) = 2rc + (1-r)(1-c) = 2rc + 1-r-c +rc = (3c-1)r +(1-c)$$

Since Mr. Row is selecting $$r$$ the key term in this payout equation is $$(3c-1)$$. This implies that:

$$
r^* = \left\{\begin{matrix}
0& if \; \; c < \frac{1}{3}\\
1& if \; \; c > \frac{1}{3}\\
[0,1]& if \; \; c = \frac{1}{3}
\end{matrix}\right.
$$

Therefore this expression will be positive when $$3c > 1$$and negative when $$3c < 1$$. Hence, Mr.Row will want to increase $$r$$ whenever $$c > \frac{1}{3}$$, decrease $$r$$ when $$c < \frac{1}{3}$$, and be happy with any value of $$0 \leq r \leq 1$$ when $$c = \frac{1}{3}$$.

Similarly, The payoff for Mr. Column is given by:

$$\pi_{column} (r,c) = rc + 2(1-r)(1-c) = rc + 2-2r-2c +2rc = (3c-2)r +2(1-c)$$

And since Mr. Column is selecting $$c$$ the key term in this payout equation is $$(3c-2)$$.This implies that:

$$
c^* = \left\{\begin{matrix}
0& if \; \; r < \frac{2}{3}\\
1& if \; \; r > \frac{2}{3}\\
[0,1]& if \; \; r = \frac{2}{3}
\end{matrix}\right.
$$

Hence, Mr. Column will want to increase $$c$$ whenever $$r > \frac{2}{3}$$, decrease $$c$$ when $$r < \frac{2}{3}$$, and will be content with any value of $$0 \leq c \leq 1$$ when $$r = \frac{2}{3}$$.

Now that we have the payoffs of both Mr. Row and Mr. Column we can plot $$r^* $$ and $$c^* $$ and find the best response curve. Starting with Row. If Column choses $$c = 0$$, Row will want to make $$r$$. as small as possible, so $$r = 0$$. is the best response to $$c = 0$$. This choice will continue to be the best response up until $$c = \frac{1}{3}$$, at which point any value of $$r$$ between 0 and 1 is a best response. For all $$c > \frac{1}{3}$$ , the best response row can make is $$r = 1$$.  Graphically we get the following:

<img src="{{ site.baseurl }}/img/gametheory/Fig30.1.PNG">

It becomes very easy to see that we have three Nash Equilibriums. Two pure strategies at $$(0,0)$$ and $$(1,1)$$--and one mixed strategy at $$(\frac{2}{3}, \frac{1}{3})$$.

**Sequential Games**

Up until now we have focused on games in which both players act simultaneously. However in many situations one player gets the first move, like in Chess or Soccer. Another example is the [Stackelberg](https://kmlv.github.io/IntermMicroecon_UCSC/Markets/) model described in the previous chapter in which one firm is the “leader” and one firm is the “follower”.  Since a certain player gets to act first, while the other player observes the choice made, sequential games are classified as dynamic games rather than static games.

To help solidify the intuition let us consider the following dynamic game with two players and the following payoff matrix:

<img src="{{ site.baseurl }}/img/gametheory/Fig29.5.PNG">

At first glance one would see a payoff matrix with two Nash equilibria: $$(Top,Left)$$ and $$(Bottom, Right)$$. However this payoff table hides the fact that in this game one player gets to know what the other player has chosen before they make their choice. In this case it is more useful to consider a diagram called the **extensive form** that illustrates the asymmetric nature of the game.

<img src="{{ site.baseurl }}/img/gametheory/Fig29.1.PNG">

With the extensive form we clearly see that Player A acts first by choosing Top or Bottom. Only *after* Player A makes their move, does Player B act. It should be noted that with this form, once Player B acts we immediately know what Player A has done.

Suppose that in our example, Player A has already made their choice and we are sitting in one branch of the game tree. If Player A has chosen top, then it doesn’t matter what Player B does, and the payoff is $$(1,9)$$. If Player A has chosen bottom, then the sensible thing for Player B to do is to choose right, and the payoff is $$(2,1)$$.

Now think about Player A’s initial choice. If they choose top, the outcome will be $$(1,9)$$ and thus they will get a payoff of 1. But if they choose bottom, they get a payoff of 2. So the sensible thing for them to do is to choose bottom. Thus the equilibrium choices in the game will be $$(bottom, right)$$, so that the payoff to Player A will be 2 and to Player B will be 1. The strategy $$(top, left)$$ is not a reasonable equilibrium in this sequential game. That is, they are not an equilibrium given the order in which the players actually get to make their choices. It is true that if Player A chooses top, Player B could choose left—but it would not be logical for Player A to ever choose top to begin with!

Generally, when dealing with sequential games we make two distinction:

1. An *action* is a move that a player makes at a specified point (blue decision node in our example).
2. A *strategy* is a <ins>complete plan</ins> that specifies the action a player will make based on information available at each decision node. (e.g Player B chooses left if Player A chooses bottom; Player B chooses right if Player A chooses top)

Moreover a strategy profile is a particular combination of strategies implemented by all players.

Each game is built by various subgames. As the name implies a subgame is a subset of a game that starts at an independent node and can be analyzed in isolation of other subgames. Our example above has three subgames one for Player A and two for Player B. Subgames are important in sequential games as they are used to find a **subgame-perfect equilibrium**. This is when a strategy profile constitutes a Nash equilibrium for every proper "subgame". At first glance one might think this would be difficult to find the Nash equilibrium for each proper subgame. However with a method called **backwards induction** we can easily find the subgame-perfect equilibrium or rather the backwards induction equilibrium.

With basic intuition established and key terms defined we can move forward with exploring the backwards induction equilibrium. Suppose, for example, that we consider a monopolist who is facing a threat of entry by another firm. The entrant must decide whether or not to come into the market, and the incumbent then decides whether or not to cut its price in response. If the entrant decides to stay out, it gets a payoff of 1 and the incumbent gets a payoff of 9.If the entrant decides to come in, then its payoff depends on whether the incumbent fights—by competing vigorously—or not. If the incumbent fights, then we suppose that both players end up with 0. On the other hand, if the incumbent decides not to fight, we suppose that the entrant gets 2 and the incumbent gets 1.

<img src="{{ site.baseurl }}/img/gametheory/Fig29.2.PNG">

To find the equilibrium using backwards induction we start by looking at both the Incumbents subgames. We assume that all players are rational, meaning that in each subgame the action that they take is the one that will maximize their payoff. Therefore in the top subgame the incumbent is indifferent between fighting and not fighting as they both have a payout of 9. In the bottom subgame the Incumbent would choose to fight.

We have now narrowed the payout of the overall game down from three different payout down to two (since we know that the rational incumbent will not willingly select to not fight should the entrant enter). Now all that remains is to look at the entrants subgame and determine if they will stay out or enter based on the results of the Incumbents subgames.   

Examining the subgame we see that if the entrant enters they will get a payout of 1 no matter what the incumbent chooses (this practically makes sense too, as the incumbent firm would have no firm to fight, hence an equal payout).  However should the Entrant enter the game we have already known with certainty that the rational incumbent will fight so the payout for the entrant will end up being 0.

With all the subgames examined we conclude that it would be beneficial to the entrant to not enter the market. Mathematically we have two strategy profiles that are backwards induction equilibrium namely $$(Stay \; out, Fight)$$ and $$(Stay \; out, Don’t \; fight)$$ as they both have a payout of $$(1,9)$$.
