---
layout: postWithoutDate
title:  "3 Producer (Alternative Notes)"
date:   2020-05-29
permalink: "/Producer-Alt-Notes/"
---

  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript" ></script>

Until now we have explored the economic models of the Consumer (demand) side. In this chapter we will focus on the various economic models that make up the producer side, also known as the supply side.

One of the simplest descriptions of the producer side deals with the idea of production. In its simplest form production is when a firm take a set of inputs and transforms those inputs into a set of outputs.

Examples of inputs or the factors of production are things such as capital, land, labor, or raw materials.

The firm then converts these inputs to get the desired output which can be a good or service. As a quick example think of all the inputs that go into producing a single smoothie. They include all the ingredients for the smoothie, along with the tools to create the smoothie like a blender, and the time it takes the individual to produces the smoothie.

To fully understand the producer side we will first discuss the individual building blocks separately and then we will how they come together

## 3.1 Technology

We start with the concept of technology. Technology is broader than the tech gadgets that we use in our daily life. It is a term used by economists to describe the knowledge used to transform inputs into outputs. Moreover this knowledge allow firms to determine the quantity of output that is feasible to attain for a given set of inputs.

However nature imposes technological constraints on firms: only certain combinations of inputs are feasible ways to produce a given amount of output, and the firm must limit itself to a technologically feasible plan of production. How does a firm do this? Well, the easiest way to this is by creating a set of all combinations of inputs and outputs that are technologically feasible. We call this the **production set**. The key takeaway of the production set is that it shows the *possible* technological choices facing the firm.

The **production function** is used to graphically show what is feasible and what is not feasible. All outputs that lie on or *within* the production function are apart of what is called the efficiency frontier. The boundary of the production function is the maximum possible output that is feasible as if the output was above the production function it would not be feasible.

The following diagram below illustrate is one example of how a production function can look (where $$q=\sqrt{3L}$$):

<iframe src="https://www.desmos.com/calculator/a6bz4ehkkn?embed" width="500px" height="500px" style="border: 1px solid #ccc"></iframe>

Mathematically we use $$q = f(L,K)$$ to denote the production function where:

* $$q = \;$$ Output (our textbook uses $$y$$ to denote output)
* $$K = \;$$ Capital (i.e tools or appliances used in the production of a good)
* $$L = \;$$ Labor (i.e employees that work for the firm)

Some examples of possible production functions are the following (remember that every input and output is expressed in units per unit of time):

*  $$q$$ = $$ f(L,K)=L+K$$
*  $$q$$ = $$ f(L,K)=L×K^2$$
*  $$q$$ = $$ f(L)=L^{0.5}$$
*  $$q$$ = $$ f(L,K)=min\{L,\frac{K}{0.5}\}$$

Lastly, before we move on we must touch on some important properties about technology. $$\\$$

As in the case of consumers, it is common to assume certain properties about technology. First we will generally assume that technologies are monotonic: if you increase the amount of at least one of the inputs, it should be possible to produce at least as much output as you were producing originally. This is sometimes referred to as the property of free disposal: if the firm can costlessly dispose of any inputs, having extra inputs around can’t hurt it.

Second, we will often assume that the technology is convex. This means that if you have two ways to produce $$q$$ units of output, $$(x_1, x_2)$$ and $$(z_1, z_2)$$, then their weighted average will produce at least $$q$$ units of output.


# Isoquants

Above we saw an graphical example of single input and its corresponding output, yet we also saw examples of production function with several inputs (namely $$L$$ and $$K$$). It suffices to say that the concept of a production function applies equally well if there are several inputs. If, for example, we consider the case of two inputs, the production function $$f(L,K)$$ would measure the maximum amount of output $$q$$ that we could get if we had $$L$$ units of labor and $$K$$ units of capital.

In the two input case the **isoquant** is a convenient way to depict the production relation. Simple put An isoquant is the set of all possible combinations of inputs 1 and 2 that are just sufficient to produce a given amount of output. Another great feature about the isoquant is that they are similar to Indifference curves. The main difference between the two is that Isoquants are labeled with the amount of output they can produce, not with a utility level. Thus the labeling of isoquants is fixed by the technology and doesn’t have the kind of arbitrary nature that the utility labeling has.

Since we already know a lot about indifference curves, it is easy to understand how isoquants work. Let’s consider a few examples of technologies and their isoquants.

**Note**: in the following three discussion (and in our textbook) the input factors have been labeled as  $$x_1$$ and $$x_2$$ arbitrarily . Remember in our notes and video lectures we will primarily see the inputs labeled as labor ($$L$$) and capital ($$K$$).

# Cobb-Douglas Isoquants

If the production function has the form $$f(x_1,x_2) = Ax_1^ax_2^b $$, then we say that it is a Cobb-Douglas production function. This is just like the functional form for Cobb-Douglas preferences that we studied earlier. The Cobb-Douglas isoquants have the same nice, well-behaved shape that the Cobb-Douglas indifference curves have; as in the case of utility functions, the Cobb-Douglas production function is about the simplest example of well-behaved isoquants.

# Fixed Proportions (Perfect complements) Isoquants

Suppose that we are producing holes and that the only way to get a hole is to use one man and one shovel. Extra shovels aren’t worth anything, and neither are extra men. Thus the total number of holes that you can produce will be the minimum of the number of men and the number of shovels that you have. We write the production function as $$f(x_1,x_2) = min \{x_1,x_2\}$$. Note that the Isoquant are just like the indifference curves of perfect complements in consumer theory.

<img src="{{ site.baseurl }}/img/producer_alt/Fig19.2.PNG">

# Perfect Substitutes Isoquants

Suppose now that we are producing homework and the inputs are red pencils and blue pencils. The amount of homework produced depends only on the total number of pencils, so we write the production function as $$f(x_1,x_2) = x_1 + x_2$$. The resulting isoquants are just like the case of perfect substitutes in consumer theory

<img src="{{ site.baseurl }}/img/producer_alt/Fig19.3.PNG">


# Marginal Product and Average product

An important notion in technology is that of marginal product.

We have the marginal product of labor which is how much extra output a firm receives from increasing the usage of labor and holding capital constant--denoted by$$MP_L = \frac{\partial f(L,K)}{\partial L}$$

Similarly the marginal product of capital is how much extra output a firm receives from increasing the usage of capital and holding labor constant--denoted by$$MP_K = \frac{\partial f(L,K)}{\partial K}$$

<ins>Example</ins>: let $$q =f(L,K)= LK^2$$ then the we have the $$MP_L$$ and $$MP_K$$ equal the following:

$$MP_L = K^2 \; and \: MP_K = 2LK\; ■$$

<ins>Example</ins>: let $$q =f(L,K)=\sqrt{L}$$ then the we have the $$MP_L$$ and $$MP_K$$ equal the following:

$$MP_L = \frac{1}{2}L^{-\frac{1}{2}} \; and \: MP_K = 0 \; ■$$

$$\\$$

Another important notion in technology is that of average product.

Intuitively, the average product of labor is the per-worker output. Similarly, the average product of capital is the per-machine output. Mathematically, they are given as such:

$$AP_L = \frac{f(L,K)}{L} \; and \; AP_K = \frac{f(L,K)}{K}$$

<ins>Example</ins>: let $$q =f(L,K)= LK^2$$ then the we have the $$AP_L$$ and $$AP_K$$ equal the following:

$$AP_L = K^2 \; and \: AP_K = LK \;■$$

<ins>Example</ins>: let $$q =f(L,K)=\sqrt{L}$$ then the we have the $$AP_L$$ and $$AP_K$$ equal the following:

$$AP_L = L^{-\frac{1}{2}} \; and \: AP_K = \frac{\sqrt{L}}{K} \;■$$

$$\\$$

There is an interesting relationship between the $$AP_L$$ and $$MP_L$$.

If $$MP_L > AP_L$$ then it must be that $$AP_L$$ is increasing with $$L$$. Similarly, If $$MP_L < AP_L$$ then it must be that $$AP_L$$ is decreasing with $$L$$.

Consider the following <ins>example</ins>: let $$L=100$$ and $$q = 1000$$. The average product is:

$$AP_L = \frac{1000}{10} = 10$$

Now suppose that the $$MP_L = 50$$ this means that if $$L=101$$ then $$q=1050$$. Now the average product is:

$$AP_L^\prime = \frac{1050}{50} > 10 \;■$$

This shows us that if the average per-worker output is less than the marginal product of labor then an increase in labor will pull up the average product of labor. The converse will be easy to see if we let $$MP_L = -50$$ (since clearly -50 < 10).

# Technical Rate of Substitution  

The next important notion in technology is the technical rate of substitution (TRS). Intuitively, this concept is analogous to the the concept of MRS seen in consumer theory. The technical rate of substitution measures the tradeoff between two inputs in production. It measures the rate at which the firm will have to substitute one input for another in order to keep output constant.

Suppose you increase $$L$$ by $$\Delta L$$. How much can you reduce $$K (-\Delta K)$$ such that the production level is not altered? Mathematically the $$TRS$$ is a measure of how steep the isoquant is--as it is the derivative of $$K$$ with respect to $$L$$, along an isoquant curve.

$$TRS = \frac{dK}{dL} = -\frac{MP_L}{MP_K}$$

<ins>Example</ins>: Find the $$TRS$$ of the following production function: $$q = L^{\frac{1}{2}}{K^2}$$. the formula for $$TRS$$ is as follows:

$$TRS = \frac{dK}{dL} = -\frac{MP_L}{MP_K}$$

Thus the $$TRS$$ is given by:

$$TRS = \frac{dK}{dL} = -\frac{MP_L}{MP_K}= \frac{\frac{1}{2}L^{-\frac{1}{2}}K^2}{2L^{\frac{1}{2}}K} = -\frac{1}{4}\frac{K}{L} ■$$

$$\\$$

# Diminishing Marginal Returns

Suppose that we have certain amounts of factors 1 and 2 (we have been using labor and capital) and we consider adding more of factor 1 while holding factor 2 fixed at a given level. What might happen to the marginal product of factor 1? As long as we have a monotonic technology, we know that the total output will go up as we increase the amount of factor 1. But it is natural to expect that it will go up at a decreasing rate. Consider this example, the case of farming.

One farmer with one acre of land might produce 100 bushels of corn. If we add another farmer and keep the same amount of land, we might get 200 bushels of corn, so in this case the marginal product of an extra worker is 100. Now keep adding workers to this acre of land. Each worker may produce more output, but eventually the extra amount of corn produced by an extra worker will be less than 100 bushels. After 5 or 6 farmers are added the additional output could start to fall. If we get hundreds of workers crowded together on this one acre of land, an extra worker may even cause output to go down. Thus, We would typically expect that the marginal product of a factor will diminish as we get more and more of that factor.

This example highlight a common feature of many production processes called Diminishing Marginal Product ($$DMR$$).


Mathematically, to see if there is $$DMR$$ of labor or capital we simply must take the second derivative of the production function and see what sign it has.   

<ins>Example</ins>: Suppose that our production function is $$q= L^{\frac{1}{2}}K^2$$. Then the marginal product of labor is:

$$MP_L = \frac{1}{2}L^{-\frac{1}{2}}K^2$$

$$DMR$$ of capital exist if $$MP_L$$ decrease with $$L$$ i.e id the partial derivate of $$MP_L$$ with respect to $$L$$ is less than zero

$$\frac{\partial MP_L}{\partial L} = -\frac{1}{4} L^{-1.5}K^2 < 0$$

Hence this production function exhibits $$DMR_L$$

Next we check for $$DMR$$ of capital

$$MP_K = 2L^{\frac{1}{2}}K$$

$$DMR$$ of capital exist if $$MP_K$$ decrease with $$K$$ i.e id the partial derivate of $$MP_K$$ with respect to $$K$$ is less than zero

$$\frac{\partial MP_K}{\partial K} = 2L^{\frac{1}{2}} > 0$$

Hence this production function does not exhibit $$DMR_K $$ ■


Note that the diminishing marginal returns is **NOT** the same as diminishing technical rate of substitution. The diminishing marginal product is an assumption about how the marginal product changes as we increase the amount of one factor, *holding the other factor fixed*. Diminishing TRS is about how the ratio of the marginal products--the slope of the isoquant--changes as we increase the amount of one factor and *reduce the amount of the other factor so as to stay on the same isoquant*.

# Return To Scale

Previously we discussed the idea of marginal product and how we would hold all but one factor of production constant to observe how the output quantity responded. However in some cases it is beneficial for the firm to scale up across all factors (inputs and outputs). This is where the idea of **return to scale (ROS)** comes in. ROS helps us in answering questions such as:

$$Will \; my \; output \; double \; if \; I \; double \; all \; my \; inputs?$$

By answering this question we will find out if our *technology is scalable*

Return to scale has a mathematical definition in which the production function can exhibit one of three possible outcomes

* **Constant return to scale (CRS)**: when a percentage $$t$$ increase in input corresponds to a $$t$$ percentage increase in output

$$f(t L , t K) = t f(L,K)$$

* **Increasing return to scale (IRS)**: when a percentage $$t$$ increase in input corresponds to a larger percentage increase in output

$$f(t L , t K) > t f(L,K)$$

* **Decreasing return to scale (DRS)**: when a percentage $$t$$ increase in input corresponds to a smaller percentage increase in output

$$f(t L , t K) < t f(L,K)$$

(Note that in all three of these outcomes $$t > 1$$)

Some technologies allow for proportional scaling up of your production operation. Some other technologies do not. Why is this?

1. CRS: Easy replication (e.g flyer distribution: 1 hour = 1000 flyers handed out, 2 hours = 2000 flyers handed out)

2. IRS: Occurs often with greater *specialization* of L and K (e.g. a larger plant more productive than two small plants).

3. DRS: Occurs often because of the difficulty in organizing/coordinating/*searching* activities as firm size increases (e.g. mining).

The following diagram depicts the three return to scale outcomes. You can see how isoquants behave in the various scenarios

<img src="{{ site.baseurl }}/img/producer_alt/ROS.PNG">


Now that we understand the definition of ROS and the intuition behind ROS we can look at a couple of examples.

<ins>Example</ins>: Consider the production function $$q = L + K$$. The goal is to compare the "new" output $$f(tL, tK)$$ to the "old" output $$tf(L,K)$$.

$$tL + tK \; vs. \; t(L+K) = tL+tK$$

We see that $$f(tL,tK) = tf(L,K)$$. Therefore this production function exhibits constant return to scales ■

<ins>Example</ins>: Consider the production function $$q = LK^2$$. As in the previous example the goal is to compare $$f(tL, tK)$$ to $$tf(L,K)$$.

$$(tL)(tK)^2 = t^3 LK^2 \; vs. \; tLK^2 \\$$

$$LK^2$$ is the common term so we can divide that out. This leaves us with $$t^3 > t$$ and Therefore this function exhibits increasing return to scales. ■

Before we wrap up our ROS discussion we have to mention a very important aspect of ROS. The notion of "return to scale" is a **local notion**. This means that ROS is not a feature that applies to all production function at any combination of labor and capital. Rather one production function can have some combinations of labor and capital in which ROS is constant, while some other production function can have a combination of labor and capital in which ROS is increasing or decreasing.

Some Prodution function have global return to scales such as $$q = LK$$ but not all. As an example consider $$q=f(L,K)=(L+K)+(K+L)^2 −0.1(K+L)^3$$

* First start at $$(L,K)= (0.5,0.5)$$
* Now set the scaling input to $$t = 2$$
* Then set the scaling input to $$t = 10$$
* You can compare the two in this Desmos [example](https://www.desmos.com/calculator/fmhcyrwfud)

#Long Run and Short Run of the Firm

The last thing we will discuss before we move onto the next section is Long run and Short run of the firm. Over the next few section we will become familiar with how the long run and short run behave on the producer side. For now we will differentiate the two as such:

1. If all factors can be adjusted, **the firm is in the "long run" (LR)**.

2. If at least one factor cannot be adjusted, **the firm is in the "short run" (SR)**

That is to say that the firm in the short run when some factor(s) must stay fixed. Typically, in the short run, capital is held fixed at $$K = \bar{K}$$. Therefore the typical production function in the short run is:

$$q = f(L,\bar{K})$$
$$\\$$

## 3.2 Cost Minimization

Up until know we have discussed the firms technology--the knowledge that goes into turning inputs into outputs. However, as you may have noticed we have not discussed any decisions the firm could make. The goal of this section is to introduce the decision making process the firm undertakes to determine what combination of labor and capital produces an specific output at the lowest cost possible. We call this **cost minimization** and we begin with the cost minimization problem.

# The Cost Minimization Problem and Isocosts

We start our discussion with the cost minimization problem. Firms operate in two kinds of markets, which we introduce with the following example.

Think of a new smoothie shop. The shop will first have to hire workers, purchase the ingredients, and purchase blenders (among other appliances). These are all inputs that are required to make smoothies, and therefore they are all found on what is called the the **input markets**. The final product--i.e the smoothies--that is produced then get sold to the consumers in what is called the **final market**.

So we see that a firm will be operating is two different markets:

1. Input markets (also called factor markets)
2. Final product markets

To understand how cost minimization works we will focus on the first markets. For now assume that the firm has already decided of a target production level denoted by $$q_0$$ (i.e an Isoquant). Then the goal of the firm is to achieve $$q_0$$ in the most efficient way. However, the only factors that the firm can control right now is how much of inputs is uses. Therefore, in order for the firm to be efficient (in this context) it must find the the "right" combination of $$(L,K)$$ to achieve $$q_0$$.

Naturally you might be asking:

$$What \; is \; the  "right"  combination?$$

The answer to that is: the right combination is the one that minimize the cost of producing the given target level of output $$q_0$$. Hence, we have the cost minimization problem

Suppose that the wages rate paid per unit of time to the firms labor is denoted by $$w$$ and the rental rate paid per unit of capital is denoted by $$r$$, mathematically we can describe the cost minimization problem with the following linear combination:

$$minimize \; cost = wL+rK \quad \quad subject \; to: f(L,K) = q_0$$

($$wL$$ is the wage rate times the number of labor hours used and $$rK$$ as the rental rate times the number of machine hours used by the firm)

Now suppose that we know that our cost is $50 with the price of wages is $20 and the price of capital is $10

$$20L +10K = 50$$

This is an example of an **isocost line** at the cost of $50 and all the combinations of labor and capital that satisfy the equation will be on this isocost line. Generally speaking an isocost curve shows the combination of input usage that cost the same (normally denoted as $$ $C$$). Note that--similar to the budget line we saw in consumer theory--every point on an isocost curve has the same cost, $$C$$, and higher isocost lines are associated with higher costs.

There are two ways to draw the isocost line:

1. Point-slope: solve for $$K$$ to get the slope and $$K$$-intercept
2. Solving for the intercepts $$K$$ and $$L$$: set $$K=0$$ and solve for $$L$$ to get the $$L$$-intercept, Set $$L=0$$ to find K-intercepts.

Try graphing our earlier example of the isocost using both these methods. What you should see is that the two intercepts of the isocost line are $$\frac{C}{r}$$ and $$\frac{C}{w}$$.

Now that we are familiar with the cost minimization problem and isocost, we can build on our previous intuition and solve the problem. Conceptually, the goal of the cost minimization problem is the find the best isocost (in this case the lowest isocost) given the required isoquant. This is analogous to what we did with the budget line in our discussion on consumer theory.

<img src="{{ site.baseurl }}/img/producer_alt/Fig21.1.PNG">

As you can see the choice of factors that minimize the production cost can be determined by finding the point on the isoquant that has the lowest associated isocost

Naturally, if out target output $$c$$ increases (or decreases) then we will see the isocost curve shift outwards (or inwards). If the price of $$w$$ or $$r$$ increases (or decreases) then the isocost line will shift towards the origin (or away from the origin).

# The Math of the Cost Minimization Problem

Now that we have build up the intuition behind the cost minimization problem and isocosts it is time to look at the math behind solving the cost minimization problem.

We will explore three different mathematical solutions to the cost minimization problem: tangency solutions, corner solutions, and kink solutions.

Recall that the goal is to minimize $$wL + rK$$ subject to $$f(L,K)=q_0$$

# Tangency Solution

In most cases if the technology of the firm satisfies the the convexity and monotonicity properties, then we can use tangency solutions to solve the cost minimization problem. As the name suggest the optimal solution is found when the slope of the isocost line is tangent to the slope of the isoquant curve (TRS). Thus the equation is:

$$-\frac{w}{r} = -\frac{MP_L}{MP_K} \implies \frac{w}{r} =\frac{MP_L}{MP_K} \quad (EQ.1) $$

With the constraint:

$$f(L,K) = q_0 \quad (EQ.2)$$

This create a system of two equations with two unknown variables.

<ins>Example</ins>: Let $$q_0 = f(L,K) = LK$$. Since we already have our constraint, to remains to solve the tangency condition:  

$$ \frac{MP_L}{MP_K} =\frac{K}{L} = \frac{w}{r} \implies rK = wL$$

Thus all that is left is to solve this system of equation. From the tangency condition we have that:

$$K = \big(\frac{w}{r}\big)L$$

Plugging into the constraint we get:

$$ L (\big(\frac{w}{r}\big)L) = q_0 \implies L^2\big(\frac{w}{r}\big) = q_0$$

Solving for $$L$$ we see that our optimal labor level is:

$$L^* = \big(\frac{qr}{w}\big)^{\frac{1}{2}}$$

Plugging $$L^* $$ into either the tangency condition or the constraint will give you the optimal capital level:

$$K^* = \big(\frac{qw}{r}\big)^{\frac{1}{2}}$$

Therefore the minimized cost is:

$$ C = w\big(\frac{qr}{w}\big)^{\frac{1}{2}} + r\big(\frac{qw}{r}\big)^{\frac{1}{2}} \implies C = 2\sqrt{qwr} ■$$

# Corner Solution

Corner solutions for cost minimization are treated similarly to corner solutions in consumer optimal choice. The best example of corner solutions is in the case of perfect substitutes--although it is not limited to just perfect substitutes. Therefore the perfect substitute isoquant can be defined as:

$$q_0 = f(L,K) = aL +bK$$

We are dealing with perfect substitute technology--this means that labor and capital are perfect substitutes. Thus the firm will use whichever is cheaper, which we can find by comparing the TRS of the isoquant with the slope of isocost.


* If the slope of the isoquant is greater than the slope of the isocost then labor is the cheaper option.
* If the slope of the isoquant is less than the slope of the isocost then capital is the cheaper option.
* Lastly, If the slope of the isoquant is equal to the slope of the isocost then any combination of capital and labor on the isoquant is the cheapest option.

<ins>Example</ins>: Let $$q_0 = 5L +10K$$ with $$w=20$$ and $$r=50$$. Also let the target output be $$q_0 = 1000$$

First note that $$\frac{a}{b} = \frac{5}{10}= \frac{1}{2}$$ and $$\frac{w}{r} =\frac{20}{50} = \frac{2}{5}$$

Since we see that $$\frac{1}{2}> \frac{2}{5}$$ we know that the isoquant is steeper than the isocost, we have that the optimal level of capital and labor is:

$$K^* = 0 \quad and \quad L^* = \frac{q_0}{a} = \frac{1000}{5} = 200$$

With this information we can also find the minimal cost by plugging in $$K^* $$ and $$L^* $$ into the isocost:

$$ C = wL^* + rK^* = 20(200)+50(0)= 4000 ■$$

In general the cost function can be summerized as such:

$$
C = \left\{\begin{matrix}
\frac{wq_0}{a} & if \; \; \frac{a}{b} \geq \frac{w}{r}\\
\frac{rq_0}{b} & if \; \; \frac{a}{b} < \frac{w}{r}\\
\end{matrix}\right.
$$


Alternatively with perfect substitutes we can compare $$\frac{a}{w}$$ vs $$\frac{b}{r}$$.


1. If $$\frac{a}{w} > \frac{b}{r}$$ then the firm should only use labor
2. If $$\frac{a}{w} < \frac{b}{r}$$ then the firm should only use capital
3. If $$\frac{a}{w} = \frac{b}{r}$$ then any point on the isoquant will minimize cost.

Mathematically, if $$\frac{a}{w} > \frac{b}{r}$$ the firm should only use labor (corner solution)

* Then: $$q_0=aL$$, so $$L^* =\frac{q_0}{a}$$
* Which means: $$K^* = 0$$
* Therefore: $$C = wL^* = \big(\frac{w}{a}\big)q_0$$

If $$\frac{a}{w} < \frac{b}{r}$$ then the firm should only use capital (corner solution)

* Then: $$q_0=bK$$, so $$K^* =\frac{q_0}{b}$$
* Which means: $$L^* = 0$$
* Therefore: $$C = rK^* = \big(\frac{w}{a}\big)q_0$$



# Kink Solution

The last type of solution we will go over is kink solutions. Like in the case of the corner solutions, while kink solutions are commonly seen in perfect complements, they are not limited to perfect complements.  

Recall that in the consumer theory the optimal bundle of perfect complements was found at the kink. Well, its not surprising that the in producer theory the optimal level of capital and labor is also at the kink. Specifically, the optimality condition is given by:

$$ \frac{L}{a} =\frac{K}{b} \quad (EQ.1)$$

Furthermore, the constraint is:

$$ q_0 = min\{\frac{L}{a}, \frac{K}{b}\} \quad(EQ.2)$$

Now all that is left is to solve for $$K,L$$. Plugging in $$EQ.1$$ into $$EQ.2$$ we get:

$$ q_0 = min\{\frac{L}{a}, \frac{L}{a}\} \quad by \; EQ.1$$

Therefore:

$$q_0 = \frac{L}{a} \implies L^* = aq_0$$

Pluging $$L^* $$ into $$EQ.1$$ we find that:

$$ \frac{K}{b} = \frac{aq_0}{a} = q_0 \implies K^* = bq_0$$

Lastly, the cost function is equal to

$$C = wL^* + rK^* = waq_0 + rbq_0 = q_0 (wa +br)$$


<ins>Example</ins>: Let $$q_0 = min\{ L, \frac{K}{2} \}$$, with the optimal output $$q_0 = 100$$ , $$w= 10$$ , $$r = 5$$

$$EQ.1$$ ( optimality by kink) will be $$L =  \frac{K}{2}$$.
$$EQ.2$$ (constraint) will be $$q_0 = min\{ {L}, \frac{K}{a}\} $$

Plugging $$EQ.1$$ into $$EQ.2$$ we see that: $$q_0 = min\{L,L\} = L^* $$

From $$EQ.1$$ we get that $$K^* = 2L^* = 2q_0$$.

Since $$q_0 = 100$$, $$K^* = 200$$ and $$L^* = 100$$ the cost function is given by:

$$C = 10(100) + 5(200) = 2000 ■$$


# Conditional demand in the short run

We shift gears now to something we have not previously mentioned before, however we have conceptually talked about them. The choices of inputs that yield minimal costs for the firm will in general depend on the input prices and the level of output that the firm wants to produce, so we write these choices as

$$L^* = L(w,r,q_0) \quad and \quad K^* = K(w,r,q_0)$$

These are called the **conditional factor demand functions** (of labor and capital respectively). They measure the relationship between the prices and output and the optimal factor choice of the firm, *conditional* on the firm producing a given level of output, $$q_0$$. Optimal cost is the cost fuction--that is:

$$c(w,r,q_0) = wL(w,r,q_0)+rK(w,r,q_0)$$

**Notice**: all of this is in the long run since we are able to adjust all inputs (refer back to the end of 3.1).

So as you see, throughout this section you have conceptually been exposed to the conditional factor demand functions

But now we move on to the next concept which is the **short run conditional demand for labor**. Recall that the short run of firm was the situation where capital was fixed i.e $$K = \bar{K}$$. Therefore the short run conditional demand of labor: $$L^{* SR} =L(w,r,q_0,\bar{K})$$. This demand is obtained by solving $$L$$ from $$q_0 = f(L, \bar{K})$$.

<ins>Example</ins>: Suppose that we have $$q_0 = L^{\frac{1}{2}}K^{\frac{1}{2}}$$ with a target output of $$q_0 = 100$$ and a fixed capital of $$\bar{K} = 25$$. We need to solve for $$L^{* SR}$$:

$$q_0 = 100 = L^{\frac{1}{2}} (25)^{\frac{1}{2}} \implies L^{* SR} = 400 ■$$

Now you may be wondering how tangency solutions play a role in all this--after all the example above is a Cobb-Douglas technology. Well tangency solution (and for that matter corner and kink solutions) wont play much of a role since capital is fixed there is no guarantee that--in this case-- the isocost is tangent to the isoquant. That is one of the key takeaway from this, since capital is fixed, only by coincidence will the long run and short run solution be the same.


## 3.3 Cost Curves

In the previous section we introduced the concept of the cost function. in this section we will explore concepts regarding how the cost function can be observed and classified. We will start with developing some intuition behind the cost function and some of the other cost related functions we derive from the cost function. We will end the section with a discussion of how cost curve behave in the long run vs the short run.

# Total, Average, and Marginal Cost.

We begin this section with and introduction to Cost curves. Consider the cost function described in the last chapter. This is the function $$c(w,r,q)$$ that gives the minimum cost of producing output level $$q$$ when factor prices are $$(w,r)$$. In the rest of this chapter we will take the factor prices to be fixed so that we can write cost as a function of $$q$$ alone, $$c(q)$$.

Going back to the previous section, we discussed that some of the costs of the firm are independent of the level of output of the firm. These types of costs are fixed costs. For example, the firm might have mortgage payments that are required no matter what its level of output. Other costs change when output changes--these are the variable costs. For example, the cost of materials will fluctuate based on output levels.

The total costs of the firm can always be written as the sum of the variable costs, $$c_v(q)$$, and the fixed costs, $$F$$:

$$c(q) = c_v(q) + F$$

The **average cost function ($$AC$$)** measures the cost per unit of output. The **average variable cost function ($$AVC$$)** measures the variable costs per unit of output, and the **average fixed cost function ($$AFC$$)** measures the fixed costs per unit output. By the above equation:

$$AC(q)=\frac{c(q)}{q}=\frac{c_v(q)}{q}+\frac{F}{q} =AVC(q)+AFC(q)$$

**Note**: Fixed cost does not depend on $$q$$ but average fixed cost does depend on $$q$$. This implies that $$AFC$$ will never increase in $$q$$, as $$q$$ is only found in the denominator.

The following diagram depicts the behavior of the three different cost functions

<img src="{{ site.baseurl }}/img/producer_alt/Fig19.3.PNG">

There is one more cost curve of interest: the **marginal cost curve (MC)**. The marginal cost curve measures the change in costs for a given change in output. For example, a firm is producing 50,000 laptops with a total cost of 1,000,000 dollars. The marginal cost measures the change in cost if the firm decided to produce one more laptop. Mathematically:

$$MC = c^{\prime} (q) = \frac{\partial c(q)}{\partial q} = \frac{\partial c_v (q)}{\partial q}$$

Notice that since fixed cost is not dependent on $$q$$ it is treated as a constant when calculating the $$MC$$, hence the marginal cost can been viewed as the marginal variable cost.

# Geometry and Relations of Cost Curves

Using the following interactive [graphs](https://www.econgraphs.org/graphs/micro/producer_theory/cost_curves) from EconGraphs you can see how all the cost curve we introduced behave with one another. Most notable you should notice the following (these point are also highlighted in the video lecture):

1. The $$MC$$ is the slope of the a tangent line of $$c(q)$$ at $$q$$ level
2. The $$AC$$ is the slope of the ray form the origin to $$c(q)$$ at $$q$$ level
3. $$MC = AVC$$ at zero units of output (since $$AVC$$ starts at the origin)
4. The $$MC$$ crosses the $$AC$$ and $$AVC$$ at their respective minimum points (since $$MC < AC$$ when $$AC$$ is decreasing and $$MC > AC$$ when $$AC$$ is increasing.)


The following Desmos also illustrate the final two points very nicely

<iframe src="https://www.desmos.com/calculator/qwnpqyzwwj?embed" width="500px" height="500px" style="border: 1px solid #ccc"></iframe>

Now lets look at an example that really ties together everything we have discussed up until now:

<ins>Example</ins>: Suppose our cost function is $$c(q) = 1 +q^2$$. It should be clear that our fixed cost $$F=1$$, and our variable cost is $$VC = c_v(q) = q^2$$. Next we find the $$AC$$ function:

* $$AVC (q)$$ = $$\frac{c_v (q)}{q} = \frac{q^2}{q} = q$$
* $$AFC (q)$$ = $$\frac{F}{q}$$
* $$AC  (q)$$ = $$\frac{c(q)}{q} = \frac{1 + q^2}{q} = \frac{1}{q} + q$$

Next we find the $$MC$$ function:

* $$MC (q)$$ = $$\frac{\partial c}{\partial q} = 2q$$

With the functions defined we can plot them on a diagram

<iframe src="https://www.desmos.com/calculator/lxu5g8abjn?embed" width="500px" height="500px" style="border: 1px solid #ccc"></iframe>  ■

# Returns to Scale

You might wonder what role returns to scale plays here. Recall that a technology is said to have increasing, decreasing, or constant returns to scale as $$f(tL,tK)$$ is greater, less than, or equal to $$tf(L,K)$$ for all $$t > 1$$. It turns out that there is a nice relation between the kind of returns to scale exhibited by the production function and the behavior of the cost function.

Suppose first that we have the natural case of constant returns to scale. Imagine that we have solved the cost-minimization problem to produce 1 unit of output, so that we know the **unit cost function**, $$c(w,r,1)$$. Now what is the cheapest way to produce $$q$$ units of output? Simple: we just use $$q$$ times as much of every input as we were using to produce 1 unit of output. This would mean that the minimal cost to produce y units of output would just be $$c(w, r, 1)q$$. In the case of constant returns to scale, the cost function is linear in output.

What if we have increasing returns to scale? In this case it turns out that costs increase less than linearly in output. If the firm decides to produce twice as much output, it can do so at *less* than twice the cost, as long as the factor prices remain fixed. This is a natural implication of the idea of increasing returns to scale: if the firm doubles its inputs, it will more than double its output. Thus if it wants to produce double the output, it will be able to do so by using less than twice as much of every input.

But using twice as much of every input will exactly double costs. So using less than twice as much of every input will make costs go up by less than twice as much: this is just saying that the cost function will increase less than linearly with respect to output. Similarly, if the technology exhibits decreasing returns to scale, the cost function will increase more than linearly with respect to output. If output doubles, costs will more than double.

These facts can be expressed in terms of the behavior of the $$AC$$ function as such:

* If the technology exhibits IRS, then this implies that AC is decreasing in $$q$$. (e.g. if we want to double $$q$$, we can less than double costs).

* If the technology exhibits DRS, then this implies that AC is increasing in $$q$$. (e.g. if we want to double $$q$$, we need to more than double costs).

* If the technology exhibits CRS, then this implies that AC is constant in $$q$$. (e.g. if we want to double $$q$$, we need to double costs).

# Fixed, Quasi-Fixed, and Sunk Costs

Before moving on it is important to highlight some nuanced notion that are related to fixed costs. namely they are **quasi-fixed cost** and **sunk cost**

It is natural to define fixed costs and quasi-fixed costs in a similar manner. Recall that fixed costs are costs associated with the fixed factors: they are independent of the level of output, and, in particular, they must be paid whether or not the firm produces output. Quasi-fixed costs are costs that are also independent of the level of output, but only need to be paid if the firm produces a positive amount of output. For example a mortgage is a fixed cost, while the heating and water are quasi fixed.

Remember that there are no fixed costs in the long run, by definition. However, there may easily be quasi-fixed costs in the long run. If it is necessary to spend a fixed amount of money before any output at all can be produced, then quasi-fixed costs will be present.

Sunk costs are another kind of fixed costs. The concept is best explained by example. Suppose that you have decided to lease an office for a year. The monthly rent that you have committed to pay is a fixed cost, since you are obligated to pay it regardless of the amount of output you produce. Now suppose that you decide to refurbish the office by painting it and buying furniture. The cost for paint is a fixed cost, but it is also a sunk cost since it is a payment that is made and cannot be recovered. The cost of buying the furniture, on the other hand, is not entirely sunk, since you can resell the furniture when you are done with it. It’s only the difference between the cost of new and used furniture that is sunk.

# Long Run and Short Run Cost Function

Now explore how the Cost curves behave in the long run and short run using some examples. Lets start with the long run.

<ins>Example</ins>: Suppose that we have Cobb-Douglas technology $$q=50L^{0.5} K^{0.5}$$. First we need to find conditional demands for labor and capital, then using $$L^* $$ and $$K^* $$ we find the cost function.

Utilizing the tangency solution that we saw in the previous section we find that:

$$\frac{MP_L}{MP_K} = \frac{w}{r} \implies \frac{K}{L} = \frac{w}{r} \implies rK = wL \quad (EQ.1) \\$$

$$q=50L^{0.5} K^{0.5} \quad (EQ.2)$$

Solving the system of equations with two unknowns by plugging $$EQ.1$$ into $$EQ.2$$ we get

$$q = 50L^{0.5} \big(\frac{w}{r} L \big)^{0.5} = 50L\big(\frac{w}{r}\big)^{0.5} \implies L^* = \frac{q}{50}\big(\frac{r}{w}\big)^{0.5} $$

Plugging $$L^* $$ into one of the two equations we find that:

$$K^* = \frac{q}{50}\big(\frac{w}{r}\big)^{0.5} $$

Now that we have $$K^* $$ and $$L^* $$ we can find the cost function:

$$c(q,w,r) = w\frac{q}{50}\big(\frac{r}{w}\big)^{0.5} + r\frac{q}{50}\big(\frac{w}{r}\big)^{0.5} \implies \frac{q}{50} \sqrt{w} \sqrt{r} + \frac{q}{50} \sqrt{w} \sqrt{r} = \frac{q}{25} \sqrt{wr} \\$$

$$c(q,w,r) = \frac{q}{25} \sqrt{wr} $$

Now that we have found the cost function we can find the $$AC$$ and $$MC$$

$$AC(q,w,r) = \big(\frac{1}{25}\big)(wr)^{0.5} \\$$

$$MC(q,w,r) = \big(\frac{1}{25}\big)(wr)^{0.5}  ■$$


This is an example of the cost function in the long run since we are able to adjust all factors--both labor and capital. Now we will see how the short run compare to the long run

<ins>Example</ins>: Let us use the same Cobb-Douglas technology as in our last example with one change. Since we are dealing with the short run capital will be fixed $$K= \bar{K}$$. Therefore $$q=50L^{0.5} \bar{K}^{0.5}$$. In this case it suffices to only solve for $$L^* $$.

$$L^{0.5} = \frac{q}{50} \frac{1}{\bar{K}^{0.5}} \implies L^{* SR} = \frac{q^2}{50^2 \bar{K}} $$

We now plug this into the short run cost function:

$$c^{sr} (q,w,r,\bar{K}) = wL^{* SR} + rK = w\big(\frac{q^2}{50^2 \bar{K} } \big) + r\bar{K} $$

Now we have the cost function and with it we can find the $$AC$$ and the $$MC$$

$$AC^{SR} (q,w,r, \bar{K}) = \frac{c^{SR}}{q} = w\big(\frac{q}{50^2 \bar{K} } \big) + r\frac{\bar{K}}{q} \\$$

$$MC^{SR} (q,w,r, \bar{K}) = \frac{\partial c^{SR}}{\partial q} = 2w\big(\frac{q}{50^2 \bar{K} } \big) ■$$


If we set values for $$w$$ and $$r$$ we will be able to  see how different levels of capital affect the short run. The diagram below does exactly this at $$w=25$$ and $$r=100$$. The $$AC(Q)$$ is the long run average cost and $$SAC(Q)$$ are the short run average cost--at various capital levels.

<img src="{{ site.baseurl }}/img/producer_alt/SAC(Q).PNG">

What if fixed level of capital in the short run is the long run level of capital? Well then the two cost curve will coincide with one another like so:

<iframe src="https://www.desmos.com/calculator/4w18a0ypht?embed" width="500px" height="500px" style="border: 1px solid #ccc"></iframe>

Generally speaking the long run average cost curve will be the lower envelope of the short-run average costs as depicted below (note that the book uses $$y$$ as output while we use $$q$$). Notice that the short run average costs always are at least as large as the long-run average costs, and they are the same at the level of output where the long run demand for the fixed factor equals the amount of the fixed factor that you have.


<img src="{{ site.baseurl }}/img/producer_alt/Fig22.8.PNG">

## 3.4 Firm Supply

Up until now we have discussed Technology--which is a model that discussed the firm's knowledge of turning inputs into outputs. Next we discussed cost minimization and how to find the optimal levels of labor and capital that would minimize cost given a set output level. Then we discussed the Cost function in depth and the relationships between the different curves we derived.

The firm however must not only optimize in the input market i.e cost minimization, but it must also maximize in the output market i.e the someone has to tell the firm what the optimal $$q$$ is to produce. In this section we will discuss profit maximization as it will help us determine the optimal output a firm should produce.

# Before We Start

Before diving into the section, we need to review some concepts and notation, as well as introduce some new concepts.

First recall that, assuming $$c(q)$$ is the cost function, the marginal cost can be written in three different ways:

$$\frac{\partial c(q)}{\partial q} = c^\prime (q) = MC(q)$$

Next we need to introduce the notion of **revenue**. Revenue can be thought of the sales a firm makes and it is the given by the product of price $$p$$ and quantity $$q$$

$$R(q)=p × q$$

However, there is a catch. We assume that price is fixed. Soon we will see that price will be determine by the market, not the firm.

Lastly, we need talk about the Firm's constraint. The firm faces the technological constraints summarized by the production function. There are only certain feasible combinations of inputs and outputs, and even the most profit hungry firm has to respect the realities of the physical world. We have already discussed how we can summarize the technological constraints, and we’ve seen how the technological constraints lead to the economic constraints summarized by the cost function.

But now we bring in a new constraint—-or at least an old constraint from a different perspective. This is the **market constraint**. A firm can produce whatever is physically feasible, and it can set whatever price it wants, but it can only sell as much as people are willing to buy. With this in mind we can move on to the concept of Perfect competition

# Perfect Competition

The Market constraint that we mentioned just now is the key feature of **perfect combination**. That is to say that agents take market price as given (individual firms cannot influence the price level with their decisions). Perfect competition is observed when many small firms operate in the market

Therefore If a price-taking firm (at price level $$p^∗ $$ ) tries to sell a good for a higher price, then it will sell zero units. Since other firm will be selling that exact good at a lower price $$p^* $$. There is no reason for a rational consumer to pay more for a good they can buy at a lower price.

Naturally the question we now have is: If the firm charges exactly $$p^∗ $$, it can produce/sell pretty much as much as it wants. But, what is the right quantity?

We can begin to answer this question with a diagram that will help in establishing the intuition. Then we can move onto the math behind this question. The following diagram plot three curves: total revenue $$(TR)$$, total cost $$(TC)$$, and total profit (denoted as $$\pi = TR-TC$$).

<img src="{{ site.baseurl }}/img/producer_alt/TotalCostRevenueProfit.PNG">

Let unpack this diagram a bit. Notice that this diagram can be broken up to three distinct areas

1. $$TR < TC$$: When revenue is less than the cost the firm is will experience negative profit i.e $$\pi < 0$$ which is seen in the profits curve

2. $$TR = TC$$: When revenue is equal to cost the firm does not have negative profits nor does it have positive profit. It has exactly zero profit i.e $$\pi = 0$$. This is seen when the profit curve is exactly zero

3. $$TR > TC$$: When revenue is greater than the cost the firm is will experience positive profit i.e $$\pi > 0$$ which is seen in the profits curve

It should be obvious that the firm will not want to produce any quantity that yields negative or zero profits therefore the firm will want to produce quantities in which $$TR >TC$$. However out of all the points that yield positive profits there is one point that will yield that most profit--namely at "the peak of the hill" $$q=300$$. At $$q=300$$ we see that the profit curve is at its "peak" but also that at this point the gap between $$TR$$ and $$TC$$ is at its biggest.

Now that we have established some intuition with this diagram we can shift our focus on to the math behind this.

# Supply Function of a Competitive Firm

Mathematically speaking notice how the optimal quantity $$q=300$$ has a slope of zero. That means that assuming that the firm wants to maximize profits $$ \pi(q)=p×q−c(q) $$ and $$\pi(q)$$ is a smooth function with a maximum, then the optimal $$q$$ can be found by setting:

$$\frac{\partial \pi(q)}{\partial q} = 0 $$

As in consumer theory we call this the **first-order condition $$(FOC)$$**. Furthermore the $$FOC$$ implies that:

$$\frac{\partial \pi(q)}{\partial q} = 0 \\$$

$$MR(q) - MC(q) = 0 \\$$

$$p - MC(q) = 0 \\ $$

$$p = MC(q)$$

While this implication will be helpful later on, by itself, the first order condition is not sufficient as it will also identify local minimums. Going back to our diagram, the $$FOC$$ will identify two points: the local maximum at $$q =300$$ ("the peak of our profit hill") but also a local minima at $$q = 60$$ ("the bottom of our profit valley"). However we are only interested in the local maxima.

$$How \; do \;we\; distinguish\; the\; local\; maxima\; from\; the\; local\; minima?$$

Well, notice that top of the local maxima goes from positive to negative. Mathematically we can describe this with the **second-order condition (SOC)**

$$\pi^{\prime \prime} (q) = -c^{\prime \prime} (q) \leq 0 \quad or \quad c^{\prime \prime} (q) \geq 0 \\ $$

$$\frac{\partial MC (q)}{\partial q} > 0$$

By satisfying the first order condition and the second order condition we can find the $$q$$ that will maximize profit. So now you might be wondering what all this is working towards. Well we are trying to achieve something that is called the **supply function of the competitive firm**. This establish the relationship between price and optimal quantity. Furthermore this creates a mapping that the firm can to use figure out what the optimal quantity is given a certain price.

Unfortuanatly the $$FOC$$ and $$SOC$$ by themselves do not give us the supply function. In oder to get the supply function we also need to talk about the **shut down condition** vs the **operation condition**. Simply put when the firm is making a profit in will stay in operation producing $$q^* > 0$$ , other wise it is not making a profit so it wont be in operation--it would shut down and produce zero $$q= 0$$.

Mathematically we are comparing:

$$pq - c_v(q)- F \quad vs. \quad - F$$

Specifically, the firm will operate if:

$$pq - c_v(q)- F \geq -F \implies pq - c_v(q) \geq 0 \implies p \geq \frac{c_v(q)}{q} = AVC(q)$$

Therefore the firm will operate when price covers the average variable cost (AVC)!

Now we have all the necessary steps to construct the supply curve. To summarize the supply curve is the upward-sloping part of MC curve that also lies above the AVC curve.

<img src="{{ site.baseurl }}/img/producer_alt/Fig23.3.PNG">

Notice in the diagram how $$q^* = 0$$ if $$MC<minAVC$$. This highlights the shut down condition graphically.

# Identifying Total Profits Graphically

It also is important to understand how profits fit into this diagram. below you will see the same diagram as above but with the profits highlighted

<img src="{{ site.baseurl }}/img/producer_alt/Fig23.4.PNG">

Given the market price we can now compute the optimal operating position for the firm from the condition that p = MC(q). Given the optimal operating position we can compute the profits of the firm. In our diagram the area of the box is just $$p^∗ q^∗$$ (recall that out book use $$y$$ instead of $$q$$), or total revenue. The area $$q^∗ AC(q^* )$$ is total costs since:

$$ qAC(q) = q \frac{c(q)}{q} = c(q)$$

Our profits as you might have already figured out are simply difference between these two areas.

# Inverse Supply Curve

An important yet simply concept that we must discuss is the **inverse supply curve**. The inverse supply curve is the same equation of the supply curve except we have solved for $$p$$:

$$p = c^\prime(q) = MC(q)\\$$

$$ if \quad c^{\prime \prime}(q) > 0 \quad and \quad c^\prime (q) > AVC $$

So you might be thinking now that we already have price solved for in the expression of the supply curve, namely $$p = MC(q^* )$$, and you correct! In many of our example and problems we don't have to solve for $$p$$ because it is already given to us when we describe the supply curve as $$p = MC(q^* )$$. The line below the $$p=MC$$ is just a reminder to us that have to discuss a quantity such that its marginal cost is increasing ($$c^{\prime \prime}(q)$$ is positive) and that the marginal cost must be above the average variable cost ($$MC > AVC$$).

# Supply Curve: An Example

In this section we have discussed alot of new concepts as well as build on a few older concepts. Now lets take a break from that and look at an example together. in this example we will take a cost function and derive the supply and inverse supply curve

<ins>Example</ins>: Suppose that our cost function is: $$c(q) = q^2 +1$$

1. First: we need to find is the marginal cost $$MC = 2q$$.
2. Second: we equate $$MC = P$$ i.e $$p = 2q$$. This is the inverse supply curve.
3. Third: We have to make sure that $$MC> AVC$$ and in this example $$AVC = \frac{q^2}{q} = q$$. For all value of $$q>0$$ we have the $$2q \geq q$$
4. Therefore the supply curve is $$q=\frac{p}{2}$$ and the *inverse* supply is $$p = 2q$$■

# Short Run Industry Supply

Lastly, as we wrap up this section and chapter we will take a look at the what the supply curve looks in the short run.

We begin by studying an industry with a fixed number of firms, $$n$$. We let $$S_i(p)$$ be the supply curve of firm $$i$$, so that the **industry supply curve**, or the market supply curve is

$$S(p) = q_1^S (p)+ q_2^S (p)+ . . . +q_n^S (p) \\$$

$$S(p) = \sum_{i=1}^{n} q_i^S (p)$$

which is the sum of the individual supply curves. Geometrically we take the sum of the quantities supplied by each firm at each price, which gives us a *horizontal* sum of supply curves, as we see in the following diagram.

<img src="{{ site.baseurl }}/img/producer_alt/Fig24.1.PNG">

The key takeaway here is that in the short run of the industry there is a time horizon in which the number of firms is fixed. (The video lecture on the short run industry supply provides a numerical example explaining step by step how to obtain the diagram above.)
