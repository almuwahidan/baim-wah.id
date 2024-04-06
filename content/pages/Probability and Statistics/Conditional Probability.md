---
title: Conditional Probability
---

## Definition
Basically this is about [[Probability]] of one event, **IF another event has happened before.**

The notation is $P(A | B)$, and can be read as "Probability of A given B has happened before".

## Equation
The equation of such conditional probability is:
$$P(A|B) = \frac{P(A \cap B)}{P(B)}$$
The difference between conditional probability and non-conditional probability is that:
 - for denominator: instead of the whole sample size, we use the probability of the "given" event that had happened before i.e. $B$.
 - for numerator: instead of only $P(A)$, we use the intersect of events $A$ and $B$, as the intersect lives within the scope of the "given event" which is $B$.

Visually it can be explained with the image below: ![image](https://cnx.org/resources/84e1eeb22e5a2c244ec545bb8ea75d779c5c810b/fig-ch03_11_07.jpg)