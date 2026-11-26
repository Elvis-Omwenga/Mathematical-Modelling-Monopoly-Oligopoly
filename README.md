## Thesis Overview

In this thesis, I examine two classical models of competition in economics: Cournot quantity competition and Bertrand price competition. The study focuses on how firms make strategic decisions in oligopolistic markets, where the decisions of one firm influence the outcomes and decisions of its competitors.

I explore how firms interact through their production quantities and pricing strategies, using mathematical models to describe their behaviour. Particular attention is given to the construction and analysis of profit functions, best-response functions and Nash equilibria. These concepts provide a mathematical framework for understanding how competing firms make decisions and how equilibrium outcomes emerge from their strategic interactions.

The analysis considers both linear and nonlinear demand functions to investigate how different market conditions influence firms' optimal decisions and equilibrium outcomes. Through optimisation techniques and fixed-point arguments, I examine the existence and characteristics of equilibrium solutions under different competitive settings.

A central part of the study is the comparison between Cournot and Bertrand competition. In the Cournot model, firms make simultaneous decisions about production quantities, while in the Bertrand model, firms compete by setting prices. These different strategic approaches lead to different market outcomes in terms of equilibrium prices, quantities and profits.

The thesis also investigates how changes in the number of competing firms affect market outcomes, particularly the relationship between competition, market prices and firms' profitability.

Overall, the study provides a mathematical examination of strategic interaction in monopoly and oligopoly markets, demonstrating how game-theoretic reasoning, optimisation and equilibrium analysis can be used to understand competition and market behaviour.

## 1. Monopoly

Consider a monopolist facing the inverse demand function:

$$
P(Q)=a-bQ,\qquad a,b>0
$$

with constant marginal cost $c$.

The firm's profit function is:

$$
\pi(Q)=(P(Q)-c)Q
$$

Substituting the inverse demand function:

$$
\pi(Q)=(a-bQ-c)Q
$$

The first-order condition for profit maximisation is:

$$
\frac{d\pi}{dQ}=a-c-2bQ=0
$$

Therefore, the optimal monopoly output is:

$$
\boxed{Q_M^*=\frac{a-c}{2b}}
$$

The corresponding monopoly price is:

$$
\boxed{P_M^*=\frac{a+c}{2}}
$$

The maximum profit is:

$$
\boxed{\pi_M^*=\frac{(a-c)^2}{4b}}
$$

## 2. Cournot Competition

Consider an oligopoly consisting of $n$ firms producing a homogeneous product. Total market output is:

$$
Q=\sum_{i=1}^{n}q_i
$$

The inverse demand function is:

$$
P(Q)=a-bQ
$$

Assuming constant marginal cost $c$, firm $i$'s profit function is:

$$
\pi_i=(a-bQ-c)q_i
$$

The first-order condition is:

$$
\frac{\partial\pi_i}{\partial q_i}
=a-c-2bq_i-b\sum_{j\neq i}q_j=0
$$

The resulting best-response function is:

$$
\boxed{
q_i^*=\frac{a-c-b\sum_{j\neq i}q_j}{2b}
}
$$

For a symmetric equilibrium, where all firms produce the same quantity:

$$
q_1^*=q_2^*=\cdots=q_n^*=q^*
$$

The equilibrium output per firm is:

$$
\boxed{q^*=\frac{a-c}{b(n+1)}}
$$

Aggregate equilibrium output:

$$
\boxed{Q^*=\frac{n(a-c)}{b(n+1)}}
$$

Equilibrium market price:

$$
\boxed{P^*=\frac{a+nc}{n+1}}
$$

Hence, for $a>c$:

$$
\boxed{P^*>c}
$$

## 3. Bertrand Competition

Consider two firms competing through prices in a homogeneous-product market.

Assume identical constant marginal costs $c$, no capacity constraints and profit-maximising firms.

Firm $i$'s profit function is:

$$
\pi_i=(p_i-c)D_i(p_i,p_j)
$$

where $D_i$ denotes the demand allocated to firm $i$.

Under the standard Bertrand assumptions, firms have an incentive to undercut a rival charging a price above marginal cost.

The Nash equilibrium is:

$$
\boxed{p_1^*=p_2^*=c}
$$

Therefore:

$$
\boxed{P_B^*=MC}
$$

Equilibrium economic profits are:

$$
\boxed{\pi_1^*=\pi_2^*=0}
$$
