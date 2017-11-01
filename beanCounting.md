Bean Counting

Assuming the limitations of this model, every transaction that has ever occurred in the world can be modeled by this. Limit orders, and more exotic variants, ultimately result in a transaction that is captured by this model. Over-the-counter trades are precisely modeled by this. At the end of the day transactions must be accounted for and open positions need to be marked. The real world is a messy place and it is not easy for math to keep up, but it can easily model the accounting aspects.

Given a set of transactions {χ = (t; a, i, c; a', i', c')}, let

A(t; i, c; c') = Σχ {aχ : tχ = t, iχ = i, cχ = c, c'χ = c'} + {a'χ : tχ = t, i'χ = i, cχ = c, c'χ = c'}
This is the amount at time t that buyer c transacts in instrument i with seller c'. The standard theory does not distinguish the selling counterparties so we can write

A(t, i, c) = Σc' A(t, i, c , c')
The standard theory also does not distinguish the buyer, so we can abbreviate this to A(t, i); the amount you transact at time t in instrument i.

Your account balance at time t in instrument i is

B(t, i) = Σs≤t A(s, i)
Market Models