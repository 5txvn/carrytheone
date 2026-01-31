# 🧱
# Converting Base 2 to Base 4
## Notes
+ Right-to-left trick
## General Explanation
1. Start with the last two digits. Convert them from base 2 to base 10. Write this result on the right side of the answer blank.
2. Move to the next two digits, and repeat the same process until there are no more digits to move to.
## Example 1
$$10201_3=\_\_\_\__9$$
1. Take the last two digits (01), and convert them from base 3 to base 10 ($01_3=1$). Write down this result on the right (**1**)
2. Move to the next two (02), and convert again ($02_3=2$). Write down this result to the left of the 2 (**21**)
3. Move to the last digit (1), and convert again ($1_3=1$). Write down this result to the left of the 21 (**121**)
4. Final Answer: **121**
## Example 2
$$221210_3=\_\_\_\__9$$
1. Take the last two digits (10), and convert them from base 2 to base 10 ($10_3=3$). Write down this result on the right (**3**)
2. Move to the next two (12), and convert again ($12_3=5$). Write down this result to the left of the 3 (**53**)
3. Move to the next/last two (22), and convert again ($22_3=8$). Write down this result to the left of the 53 (**853**)
4. Final Answer: **853**
## Video Explanation(s)
<iframe width="560" height="315" src="https://www.youtube.com/embed/VnEzPUd920I?si=T7DIdhliwUAzOstM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br>*Written by: Steven Livingston*<br>
*Edited/Proofread by: n/a*