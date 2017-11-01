Market Models

Buyers have the choice of taking the prices presented by the sellers. Prices in the future are not known, but they can be modeled by a set, Ω. The simplest case is where Ω is simply the set of possible prices. More sophisticated models can incorporate information about other instruments or market fundamentals.

A market model is a function X:T×A×I×C×I×C→B(Ω).

We will elide the dependence on counterparties. At time t, a buyer, c, can transact amount a in instrument i for the amount -aX(ω) in instrument i' with a seller, c', where ω is the state of the world at the time of the transaction. Given a set of transaction the mark-to-market (for a market model) in instrument i is

C(t, i) = B(t, i) + Σj ≠ i B(t, j)X(t, -B(t, j), j, i)
This is the cost of liquidating your current positions in instruments j ≠ i into instrument i by doing the transactions (t; -B(t, j), j; B(t, j)X(t, -B(t, j), j, i), i) for each j ≠ i.﻿﻿

One Period Model

