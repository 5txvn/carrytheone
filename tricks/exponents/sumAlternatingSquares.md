# ⚡
# Sum of Alternating Squares
## Notes
None.
## General Explanation
Deriving the formula for sum of alternating squares ($1^2-2^2+3^2-\dots$) is rather cumbersome using legitimate algebra, so the pattern is best demonstrated by analyzing the first few cases:
1. $1^2=1$
2. $1^2-2^2=-3$
3. $1^2-2^2+3^2=6$
4. $1^2-2^2+3^2-4^2=-10$
5. $1^2-2^2+3^2-4^2+5^2=15$

If you're a bit familiar with Number Sense, hopefully you can realize that the results are the nth triangular numbers with alternating signs (notice the sign of the answer is the same as the sign of the last term). Thus, we can get the answer by taking the nth triangular and giving our answer the same sign as the last term of the summation.
## Example 1
$$1^2-2^2+\dots +13^2=$$
1. Take the last number (13) and find its triangular ($T_{13}=\frac{13\times 14}2=91$).
2. Since the last term is positive, our answer will be positive.
3. Final Answer: **91**
## Example 2
$$-1^2+2^2+\dots +8^2=$$
1. Take the last number (8) and find its triangular ($T_{8}=\frac{8\times 9}2=36$).
2. Since the last term is positive, our answer will be positive (note that the first term being negative doesn't matter!!).
3. Final Answer: **36**

## Video Explanation(s)
None.

<br>*Written by: Steven Livingston*<br>
*Edited/Proofread by: n/a*