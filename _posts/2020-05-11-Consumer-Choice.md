---
layout: post
title: "Consumer Choice"
date:   2020-05-11 
permalink: "/Consumer-Choice/"
---

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>


This section presents some standard economic models of consumer behavior. 

## 2.1 Rational Choice

The basic model of consumer choice studies the decision of a single person regarding what goods to acquire, and how much to buy of each of them, taking as given the prices of the goods and the income level of the consumer. Our simple model assumes that each consumer chooses the “best” combination of goods ---or bundle---  that “he can afford”. The idea of “best” builds on the notions of preferences and utility; our model captures “affordability” via budget sets. 

**1. Preferences:** The preferences on an individual consist of his personal ranking over all possible alternatives. We often capture these preferences by the so called utility function. 

**2. Budget set:** The budget set of an individual is the collection of all alternatives that he can afford given his resources (income or wealth) and the prices of the goods he faces in the market.

Together, (1) and (2) induce choices. That is, they determine what consumption bundles are selected by the consumer. As prices and/or income change, so does the budget set and (often) the combination of goods that the consumer selects. The demand function describes the consumption decisions for all different combinations of prices and income levels. 


To simplify the exposition, we will focus on a simple version of the consumer problem. The components of our model are as follows:

1. We assume there are only two goods: good 1 and good 2.
2. We represent the quantities of these goods as $$x_1$$ and $$x_2$$, respectively. The ordered pair $$(x_1,x_2)$$ denotes a bundle of goods. 
3. The prices of the goods are represented by $$p_1$$ and $$p_2$$, respectively.
4. The income level of the consumer is denoted by $$m$$.

<ins> Example </ins>: Suppose good 1 is orange juice and good 2 is salad. Then $$x_1$$ indicates the quantity of orange juice (say in liters) and $$x_2$$  is the quantity of salads (say in pounds). In this context, the combination (1/2, 1) represents the bundle of half liter of orange juice and one pound of salad. Suppose also that a liter of orange juice costs 5 dollars, a pound of salad costs 10 dollars, and the income level of the consumer is 500 dollars. In our notation, this information is concisely written as $$p_1$$ = 5, $$p_2$$ = 10, and $$m$$ = 500. ■



This simple two-goods model can be easily extended to more goods (e.g., it can be extended to the set of all goods you can get in the supermarket). We use the two-goods case because it helps us to illustrate the main concepts and tools in a simple way, often invoking a graphical representations of the model.

## Utility Function

Consumer preferences represent a ranking over consumption bundles or combinations of different goods. For instance, if the consumer strictly prefers bundle $$(x_1^{'},x_2^{'})$$ = (1 pizza, 2 burritos) over bundle $$(x_1^{'},x_2^{'})$$ = (2 pizzas, 1 burrito), then the first combination of goods is ranked before the second one in the preferences of this consumer.

We will always assume consumer preferences are transitive. Transitivity means that if a consumer prefers bundle $$a$$ over bundle $$b$$, and he also prefers bundle $$b$$ over bundle $$c$$, then it must be the case that the consumer prefers bundle $$a$$ over bundle $$c$$. 

Transitivity is a very important property as it allows us to talk of the most preferred bundle! When it holds, we can often conveniently represent the preferences of a given consumer by what we call a utility function.$$^1$$ 

Formally, a utility function is a function that assigns a number to each bundle in such a way that these numbers respect the underlying preference ranking of the consumer (i.e., the utility function assigns higher numbers to more preferred combinations of goods).

<ins> Example </ins>:Let good 1 be pizza and good 2 be burrito. In addition, assume the preferences of a given consumer over slices of pizza and burritos are captured by the next utility function: 

$$u(x_1,x_2) = (x_1)^{1/4} (x_2)^{3/4}$$

Suppose that a first bundle contains 16 slices of pizza and 1 burrito, so that u(16,1)=2. If a second bundle has 3 slices of pizzas and 3 burritos, then $$u(3,3)=3$$. It follows that this consumer prefers the second over the first combination of goods (i.e., he likes to have 3 slices of pizzas and 3 burritos more than having 16 slices of pizza and 1 burrito). ■

Though there are many types of utility functions, in this course we will mainly focus on three of them: Cobb-Douglas, Perfect Complements (i.e., Leontieff), and Perfect Substitutes (i.e., linear). We will sometimes also use the CES utility function. (CES stands for constant elasticity of substitution. We will clarify this term later.) The specific mathematical (functional) form of each of these utilities is given in the next table.

Utility Function | Mathematical Form
:----------------|:-----------------
Perfect Substitutes| $$u(x_1,x_2) = ax_1 + bx_2$$
Perfect Complements| $$u(x_1,x_2) = min\{ \frac{x_1}{a} , \frac{x_2}{b} \}$$
Cobb-Douglas| $$u(x_1,x_2) = (x_1)^a (x_2)^b$$
CES| $$u(x_1,x_2) = (ax_1^r + bx_2^r)^{1/r}$$


In the first three cases we typically assume $$a,b \ge 0$$. In the last one, we let $$r \leq 1$$. As we shall see, these parameters play very different roles in each specification.

As we explained earlier, the important aspect of a utility function is that it captures the underlying preferences of a specific consumer. According to the ordinal utility theory, it is meaningful to ask whether a bundle is better than a second one, but not how much better it is. In other words, the actual numbers that a utility function assigns to the specific bundles are not important as far as they preserve (respect) the ranking of the individual over the combination of goods. It follows that when the preferences of an individual can be represented by a utility function, then an infinite number of them can capture the same preferences!


<ins> Example </ins>: Suppose that our previous consumer strictly prefers 16 slices of pizza and 1 burrito to 3 slices of pizzas and 3 burritos. In addition, he is indifferent between having 3 slices of pizzas and 3 burritos and 2 slices of pizzas and 4 burritos. Moreover, he strictly prefers 2 slices of pizzas and 4 burritos to having 2 slices of pizzas and 2 burritos. In summary, this consumer ranks the different combinations of goods as follows:


$$1^{st} \; (16,1); \quad 2^{nd} \;(3,3) \; and \; (2,4); \quad 3^{rd}\; (2,2)$$


It follows that a utility function represents his preferences if and only if it assigns numbers to each combination of goods in the following way:

$$u(16,1) > u(3,3)=(2,4) > u(2,2)$$


Let us now consider the three possible utility functions shown in the next table. Which of these three utilities represent the preferences we just described?

Bundle| Utility 1| Utility 2| Utility 3
:----:|:--------:|:--------:|:--------:
$$(16,1)$$|8|12|4
$$(3,3)$$|7|9|2
$$(2,4)$$|6|9|2
$$(2,2)$$|3|2|-1

It is clear that Utility 1 does not do so. The reason is that it assigns to bundle $$(3,3)$$ a higher number than to bundle $$(2,4)$$, contradicting the fact that the consumer is indifferent between these two combinations of goods. On the other hand, even when Utility 2 and Utility 3 assign different numbers to the bundles, both of them are consistent with the preference ranking of the consumer. Therefore, Utility 2 and Utility 3 both represent this consumer’s preferences. ■

There are two concepts associated with the utility function, which play a key role in explaining consumer behavior, namely, indifference curves and marginal rate of substitution. We next elaborate on each of them.

An indifference curve is the set of all bundles that a consumer regards as equally desirable. In other words, it is the set of all combinations of goods that give the consumer the same utility level. 

We often assume that preferences satisfy a property that says more is always better. Under this monotonicity assumption, the indifference curves cannot be “thick” and they must be downward sloping. 

Weakly preferred sets also provide a convenient characterization of preferences. In terms of the utility function, a weakly preferred set is the sets of all bundles $$(x_1,x_2)$$ such that $$u(x_1,x_2)$$ is at least as large as a specific value $$k$$.


<ins> Example </ins>: Let $$u(x_1,x_2) = (x_1)^{1/4} (x_2)^{3/4}$$. Then, 

$$u(x_1,x_2) = (x_1)^{1/4} (x_2)^{3/4} = k$$

implicitly describes the set of all combinations of goods 1 and 2 that give the consumer a level k of utility. For each k, this set ---which can be also written as $$x_2 = \frac{k^2}{x_1}$$--- denotes a specific indifferent curve. We can get all the indifference curves by changing $$k$$. 

In addition, for each $$k$$, the associated weakly preferred set is $$x_2\geq \frac{k^{4/3}}{x_1^{1/3}}$$. ■

The next figure shows the typical shape of the indifference curves for the case of Perfect Substitutes (top, left), Perfect Complements (top, right), Cobb-Douglas (bottom, left) and CES (bottom, right). You can find an interactive version of this figure here:

[https://www.desmos.com/calculator/sh2hmdkie9]( https://www.desmos.com/calculator/sh2hmdkie9)  

(a) Perfect Substitutes | (b) Perfect Complements 
(c) Cobb-Douglas | (d) CES

As we will explain, the marginal rate of substitution (MRS) is intimately related with the concept of marginal utility (MU). Thus, we start describing the latter. 

The marginal utility of good 1 captures the extra utility the consumer gets if he slightly increases the consumption of good 1, while keeping fixed the consumption of the second one. We can similarly define the marginal utility of good 2. When the utility function $$u(x_1,x_2)$$ is differentiable, then the marginal utilities of goods 1 and 2 (denoted by $$MU_1$$ and $$MU_2$$) are simply the partial derivatives of $$u(x_1,x_2)$$ with respect to goods 1 and 2, respectively. That is, 

$$MU_1 = \frac{\partial u(x_1,x_2)}{\partial x_1} \quad and \quad MU_2 = \frac{\partial u(x_1,x_2)}{\partial x_2}$$


<ins> Example </ins>: $$u(x_1,x_2) = (x_1)^{1/4} (x_2)^{3/4}$$. Then, 

$$MU_1 (x_1,x_2) =\frac{1}{4}(x_1)^{-3/4} (x_2)^{3/4} \quad and \quad MU_2 (x_1,x_2) =\frac{3}{4}(x_1)^{1/4} (x_2)^{-1/4}  ■ $$

We showed before that two different utility functions might induce the same ranking over consumption bundles. These two utility functions represent the same preferences. As the next example illustrates, an issue with the concept of marginal utility is that it is sensitive to the way in which we represent consumer preferences. 

<ins> Example </ins>: Let us work with the same utility as in the previous example, $$u(x_1,x_2) = (x_1)^{1/4} (x_2)^{3/4}$$, except that now we multiply it by 4. That is, $$u(x_1,x_2)= 4(x_1)^{1/4}(x_2)^{3/4}$$. Then,

$$MU_1 (x_1,x_2) =(x_1)^{-3/4} (x_2)^{3/4} \quad and \quad MU_2 (x_1,x_2) =3(x_1)^{1/4} (x_2)^{-1/4}$$


Since this utility is just $$u(x_1,x_2)=(x_1)^{1/4} (x_2)^{3/4}$$ multiplied by 4, it represents the same ranking over consumption bundles as the utility of the previous example. Nevertheless, the two MUs are four times as large with $$u(x_1,x_2)=4(x_1)^{1/4} (x_2)^{3/4}$$ as compared to $$u(x_1,x_2)=(x_1)^{1/4} (x_2)^{3/4}$$ ■

Notice that the assumption of monotonicity implies that MUs are always positive.

As we mentioned above, a second concept related to the utility function that is very important in economics is the marginal rate of substitution (MRS). The MRS is a measure of the relative value of good 1 in terms of good 2. In particular, it measures (approximately) how much the consumer is willing to give up of good 2 in order to obtain an additional unit of good 1.


Mathematically, the MRS is given by the slope of an indifference curve (IC) at a given bundle. Therefore, it can be obtained as follows: Assuming that preferences are monotonic and can be represented by the utility function $$u(x_1,x_2)$$, we can think of an IC as a function $$x_2(x_1). Along this IC, we have:

$$u(x_1,x_2(x_1))= k$$

If we differentiate this function with respect to $$x_1$$ (using the [Chain Rule](https://en.wikipedia.org/wiki/Differentiation_rules)), we get:

$$ \frac{\partial u}{\partial x_1}(x_1,x_2) + \left[ \frac{\partial u}{\partial x_2} (x_1,x_2)\right] \frac{\partial x_2}{\partial x_1}(x_1) = 0. $$

Since the MRS is the slope of the IC, we get that

$$MRS = \frac{\partial x_2}{\partial x_1}(x_1) = \frac{-MU_1}{MU_2}.$$

A very important property of the MRS is that (unlike the marginal utilities MUs) it is not affected by the way in which we measure preferences! 

<ins> Example </ins>: Let the utility function be either $$u(x_1,x_2) = (x_1)^{1/4} (x_2)^{3/4}$$ or $$u(x_1,x_2)= 4(x_1)^{1/4}(x_2)^{3/4}$$. In both cases, we have that 

$$MRS(x_1, x_2) = \frac{-MU_1 (x_1,x_2) }{MU_2 (x_1,x_2)} = \frac{-x_2}{3x_1}$$

In other words, the MRS remains the same for both utilities.■

When the utility function increases in the consumption of each good, then the MRS is negative. This means that if the consumer sacrifices a bit of one good, then he must be compensated with a bit more of the other good to be as well as before.

In addition, we often assume that the MRS is decreasing (in absolute value). This captures the idea that the consumer prefers some sort of diversification across goods ---he prefers to have some of each good rather than having a lot of one good and nothing of the other. A decreasing MRS means that the more the consumer sacrifices one good, the more he needs to be compensated with the other one to be as well as before. When this happens, we say that consumer preferences are convex.







