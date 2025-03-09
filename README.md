<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Cell Labelling

_Labelling membrane proteins on Jurkat T-cells using primary and secondary antibodies. I'm constantly updating this repository by moving my notes to here. Let me know if you have any suggestions._

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
1. Take 1mL of cells from the flask (10^6 cells per mL)
2. Centrifuge to 50 µL (300G for 2 min) 1x
3. Pour off the buffer into a waste container.
4. Resuspend cell pellet in 50 µL of cold PBS (ideally fresh PBS).
5. Put in primary labelling buffer.
6. Leave it in the fridge for 30 min.
7. Wash out the primary using 1 mL PBS.
8. Centrifuge (300G for 2 min) 1x
9. Resuspend cell in 1 mL of 2% PFA.
10. Leave it at room temperature for 15 minutes.
11. Centrifuge (300G for 2 min) 1x
12. Pour off the buffer into a waste container.
13. Add 50 µL of cold PBS. 

### Secondary labelling
1. Take 1mL of cells from the flask (10^6 cells per mL)
2. Centrifuge to 50 µL (300G for 2 min) 1x
3. Pour off the buffer into a waste container.
4. Resuspend cell pellet in 50 µL of cold PBS (ideally fresh PBS).
5. Put in unlabelled primary buffer.
6. Leave it in the fridge for 30 min.
7. Add 1 mL PBS.
8. Centrifuge (300G for 2 min) 1x
9. Pour off the buffer into the waste container.
10. Resuspend cells in 1 mL of 2% PFA.
11. Leave it at room temperature for 15 minutes.
12. Centrifuge (300G for 2 min) 1x
13. Pour off the buffer into the waste container.
14. Resuspend cell pellet in 50 µL of coldPBS.
15. Put in secondary labelling buffer.
16. Leave it in the fridge for 30 min.
17. Add 1 mL of cold PBS
18. Centrifuge (300G for 2 min) 2x
19. Resuspend cell pellet in 50 µL cold PBS. 

#### Non-specific binding
Protocol to prepare the samples to assess and compare the non-specific binding of the secondary antibody:
1. Take 1mL of cells from the flask (10^6 cells per mL)
2. Centrifuge to 50 µL (300G for 2 min) 1x
3. Pour off the buffer into a waste container.
4. Resuspend cell pellet in 1mL BSA/PBS/cell media.
5. Leave it on ice for 30 min.
6. Spin down and take out the liquid.
7. Resuspend cell pellet in 50 µL BSA/PBS/cell media.
8. Put in secondary labelling buffer.
9. Leave it in the fridge for 30 min.
10. Add 1mL of BSA/PBS/cell media.
11. Spin and take all the liquid out.
13. Resuspend cell pellet in 50 µL cold PBS.
    
### Notes
In a light-sheet illuminated volume in an OPM microscope, there is a 2.8 nM upper concentration limit:

$C_{max} = \frac{1}{V*Na}$

$V$: the observation volume which can be calculated using light-sheet geometry.

$Na$: The Avogadro's constant. $6.02214*10^23/mol$

However, the number of molecules occupying the observation volume is fluctuating. This equation also ignores the noise that can limit the concentration of molecules. 

## Graphical Materials and Methods:

**Centrifuge**

<img src="https://github.com/astormic/CellLabelling_JurkatTCells/blob/main/Centrifuge.jpg" width="340" height="400">

## FAQs:

### Non-specific binding
To detect non-specific binding, we labelled the targets using only a secondary antibody conjugated to the Atto 647N NHS ester dye. This experiment was conducted alongside another sample that underwent the same labelling process, except the cells in the second sample were pre-incubated in 1% BSA for 30 minutes on ice (live cells). To ensure the observed signals were due to non-specific binding, both samples underwent two final washing steps. The antibody labelling ratio was 1:100 for this experiment, though we typically increase the concentration of BSA for blocking purposes.
   
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
