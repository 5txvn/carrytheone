# ✖️
# Multiplication by 111
## Notes
+ Right-to-left trick
+ Carrying required
## General Explanation
This trick is effectively the same as the multiplication by 11 trick (please refer to that first), except you add digits in groups of 3 instead of groups of 2.
1. Write down the last digit of the number of the right side of the answer blank
2. Add the last two digits of the number, and write the result to the left of the current answer. Carry if needed.
3. Add the last three digits of the number, and write the result to the left of the current answer. Carry if needed.
4. Move over one digit and add that group of 3 neighbors, continuing to write results to the left. Carry if needed.
5. Once you reach the first two digits, add those and write the result to the left. Carry if needed.
6. Once you reach the final digit, simply write it to the left of the current answer. Carry if needed.
## Example 1
$$123\times 111=$$
1. Write down the last digit (3) on the right side of the answer blank (**3**)
2. Add up the last two digits ($2+3=5$). Write this down to the left of the 3 (**53**)
3. Now add up all three digits ($1+2+3=6$). Write this down to the left of the 53 (**653**)
4. There are no more groups of 3, so add up the first two digits ($1+2=3$). Write this down to the left of the 653 (**3653**)
5. Take the first digit (1), and now write it to the left of the 3653 (**13653**)
6. Final Answer: **13653**
## Example 2
$$4567\times 111=$$
1. Write down the last digit (7) on the right side of the answer blank (**7**)
2. Add up the last two digits ($6+7=13$). Write down the 3 to the left of the 7, carry the 1 (**37**)
3. Add up the last three digits ($5+6+7=18$). Add the carry ($18+1=19$), write down the 9 to the left of the 37, and carry the 1 (**937**)
4. Move to the next group of three digits, and add them up ($4+5+6=15$). Add the carry ($15+1=16$), write down the 6 to the left of the 937, and carry the 1 (**6937**)
5. No more groups of 3, so add up the first twot digits ($4+5=9$). Add the carry ($9+1=10$), write down the 0 to the left of the 6937, and carry the 1 (**06937**)
6. Take the first digit (4), add the carry ($4+1=5$), and write this to the left of the 06937 (**506937**)
7. Final Answer: **506937**
## Video Explanation(s)
<iframe width="560" height="315" src="https://www.youtube.com/embed/ALEhj4Lcsu4?si=O5_AOpLGfNuj7wUu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>*Written by: Steven Livingston*<br>
*Edited/Proofread by: n/a*