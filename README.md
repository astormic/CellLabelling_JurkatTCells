<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Cell Labelling

_Labelling membrane proteins on Jurkat T-cells using primary and secondary antibodies._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Materials:
  - Primary Labelling Buffer (see [Protocol](https://github.com/astormic/Antibody_Dye_Conjugation/tree/main))
  - Secondary Labelling Buffer (see [Protocol](https://github.com/astormic/Antibody_Dye_Conjugation/tree/main))
  - Unlablled primary antibody
  - Phosphate buffered saline (PBS)
  - Centrifuge
  - 20/200/1000µL pipettes and tips

## Methods:
### Primary labelling
1. Take 1mL of cells from the flask
2. Centrifuge (200G for 2 min) 1x
3. Pour off the buffer into a waste container.
4. Resuspend cell pellet in 50 µL cell media.
5. Put in primary labelling buffer (1:100). Probably around 0.5 µL. 
6. Leave it in the fridge for 30 min.
7. Wash out the primary using 1 mL PBS
8. Centrifuge to 50 µL (200G for 2 min) 2x

### Secondary labelling
1. Take 1mL of cells from the flask
2. Centrifuge to 50 µL (200G for 2 min) 1x
3. Pour off the buffer into a waste container.
4. Resuspend cell pellet in 50 µL cell media.
5. Put in unlablled primary buffer (1:100). Probably around 0.5 µL. 
6. Leave it in the fridge for 30 min.
7. Wash out the primary using 1 mL PBS.
8. Centrifuge (200G for 2 min) 1x
9. Resuspend cell pellet in 50 µL cell media.
10. Put in secondary labelling buffer (1:100). Probably around 0.5 µL.
11. Leave it in the fridge for 30 min.
12. Wash out using 1 mL PBS
7. Centrifuge (200G for 2 min) 2x
8. Resuspend cell pellet in 50 µL cell media.

In a light-sheet illuminated volume in an OPM microscope, there is a 2.8 nM upper concentration limit:

$C_{max} = \frac{1}{V*Na}$

$V$: the observation volume which can be calculated using light-sheet geometry.

$Na$: The Avogadro's constant. $6.02214*10^23/mol$

However, the number of molecules occupying the observation volume is fluctuating. This equation also ignores the noise that can limit the concentration of molecules. 

## Graphical Materials and Methods:

**Centrifuge**

<img src="https://github.com/astormic/CellLabelling_JurkatTCells/blob/main/Centrifuge.jpg" width="340" height="400">

## FAQs:

### Unspecific binding
To identify unspecific bindings, we labelled the targets with only secondary antibody conjugated to a Atto 647N dye. This experiment was done in parallel with another sample that went through the same labelling process with the difference that in the second sample the cells were pre incubated in 1% BSA for half an hour on ice (live cells). To make sure the dyes observed with the microscope are due to unspecific binding, the final washing step was carried out twice for both samples. The labelling ratio for this experiment was 1:100. We tend to increase the concentration of BSA used for blocking purposes.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Feedback: [Create a pull request]()

This work is licensed under a
[Creative Commons Attribution 4.0 International][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: https://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

</footer>
