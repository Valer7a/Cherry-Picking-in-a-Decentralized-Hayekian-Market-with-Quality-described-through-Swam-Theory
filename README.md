# Cherry-Picking-in-a-Decentralized-Hayekian-Market-with-Quality-described-through-Swam-Theory
In this project is presented the computational development of the model presented in [1]. In particular, the model is articulated in two different but similar scenarios. Both are an evolution of the model presented in [2].

The dynamics is the one of a decentralized Hayekian market with simple prices adaptations and a unique good, described through swarm theory. In the model, sellers' prices are shown as in the mall or on online web-sites. Instead, buyers' reservation price (the maximum price the buyers is willing to spend) is known only by the buyer itself. The buyer chooses the seller to interact with, basing its choice on the quality and/or the price offered by sellers (more details in [1]). In particular, the dynamics that is reproduced by the pesented code, can be described in this way:

* Each buyer looks for the right seller (under the above mentioned conditions), visiting and comparing prices and qualities offered by all of them.
* After choosing the best one, the buyer will compare their prices and buy if its reservation price is higher or equal than seller's price (or not if it is not).
* If the buyer effectively makes the transaction, then its reservation price will go down (if not it will go up).
* Each seller is visited by every buyer. If they buy, then it will increase the price of the product (if not it will decrease it).

Coding language in Python.

To reach the interacting platform of Binder 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Valer7a/Cherry-Picking-in-a-Decentralized-Hayekian-Market-with-Quality-described-through-Swam-Theory/HEAD)


[1] Knopoff, D.; Secchini, V.; Terna, P. Cherry Picking: _Consumer Choices in Swarm Dynamics, Considering Price and Quality of Goods_. Symmetry __2020__, 12, 1912.


[2] Bellomo N.; De Nigris S.; Knopoff D.; Morini M.; Terna P., _Swarms dynamics approach to behavioral economy: Theoretical tools and price sequences_, Networks & Heterogeneous Media, __2020__, 15, 1556-1801
