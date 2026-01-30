# ➗
# Remainder When Dividing By 11
+ Right-to-left trick (partially)
## Notes
None.
## General Explanation
Finding the remainder when dividing by 11 is a bit more unique and complex than the other numbers. In essence, you want to start with the last digit and you're going to begin a pattern of alternating between subtraction and addition: subtract the previous digit from the last digit, then add the previous digit to that digit, then subtract the next previous digit, etc. until you reach the beginning. If your final answer is less than 0 or greater than 10, add/subtract 11 until the answer is within 0-10.
## Example 1
*What is the remainder of $12345\div 11$?*
1. Start with the last digit (5). Subtract the previous digit ($5-4=1$)
2. Add the next previous digit (3) to this result ($1+3=4$)
3. Subtract the next previous digit (2) from this result ($4-2=2$)
4. Add the last previous digit (1) to this result ($2+1=3$)
5. Final Answer: **3**
## Example 2
*What is the remainder of $90513\div 11$?*
1. Start with the last digit (3). Subtract the previous digit ($3-1=2$)
2. Add the next previous digit (5) to this result ($2+5=7$)
3. Subtract the next previous digit (0) from this result ($7-0=7$)
4. Add the last previous digit to this result ($7+9=16$)
5. Notice how 16 is greater than 10 and thus, not a valid remainder? We now need to subtract 11 until we get a valid remainder ($16-11=5$)
6. Final Answer: **5**
## Video Explanation(s)
None.

<br>*Written by: Steven Livingston*<br>
*Edited/Proofread by: n/a*