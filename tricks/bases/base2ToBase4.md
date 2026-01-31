# 🧱
# Converting Base 2 to Base 4
## Notes
+ Right-to-left trick
## General Explanation
1. Start with the last two digits. Convert them from base 2 to base 10. Write this result on the right side of the answer blank.
2. Move to the next two digits, and repeat the same process until there are no more digits to move to.
## Example 1
$$1001010_2=\_\_\_\__4$$
1. Take the last two digits (10), and convert them from base 2 to base 10 ($10_2=2$). Write down this result on the right (**2**)
2. Move to the next two (10), and convert again ($10_2=2$). Write down this result to the left of the 2 (**22**)
3. Move to the next two (00), and convert again ($00_2=0$). Write down this result to the left of the 22 (**022**)
4. Move to the last digit (1), and convert again ($1_2=1$). Write down this result to the left of the 022 (**1022**)
5. Final Answer: **1022**
## Example 2
$$110111_2=\_\_\_\__4$$
1. Take the last two digits (11), and convert them from base 2 to base 10 ($11_2=3$). Write down this result on the right (**3**)
2. Move to the next two (01), and convert again ($01_2=1$). Write down this result to the left of the 3 (**13**)
3. Move to the next/last two (11), and convert again ($11_2=3$). Write down this result to the left of the 13 (**313**)
4. Final Answer: **313**
## Video Explanation(s)
<iframe width="560" height="315" src="https://www.youtube.com/embed/VnEzPUd920I?si=T7DIdhliwUAzOstM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>*Written by: Steven Livingston*<br>
*Edited/Proofread by: n/a*