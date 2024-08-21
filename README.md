<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Conjugation of dye and antibody

_The process of attaching fluorescent molecules to antibodies._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Materials:
  - Primary Antibody:
    [Mouse anti-Human CD45 (HI30)](https://www.ptglab.com/products/CD45-Antibody-65109-1-Ig.htm)
  - Secondary Antibody:
    [Goat anti-Mouse IgG](https://www.bioscience.co.uk/product~73025)
  - Dye:
    [Atto 647N](https://www.aatbio.com/products/atto-647n-nhs-ester) supplied with an NHS (N-hydroxysuccinimde) ester reactive group.
  - Phosphate buffered saline (PBS)
  - Sodium bicarbonate (SoBi), 1M, pH8.5

## Methods:
### Buffer Exchange in Gel Filteration Column
1. Take an aliquot of protein
2. A quick spin
3. Spin for 2min (1000)
4. Run PBS 4 times (500 µL) and spin 4min (1000)
5. Run the protein through
6. Take the protein from the collection tube

### Bioconjugation for primary CD45
1. Add 2 µL of SoBi to the proteins and mix them
2. Add 2 µL of dye to the mixture
3. Take 1.5 µL of the buffer to measure the concentration using UV-Vis
4. Leave it at room temperature (1 hour)
5. Run the buffer through a new gel filteration column

### Bioconjugation for secondary
1. Add 5 µL of SoBi to the proteins and mix them
2. Add 6 µL of dye to the mixture
3. Take 1.5 µL of the buffer to measure the concentration using UV-Vis
4. Leave it at room temperature (1 hour)
5. Run the buffer through a new gel filteration column
   
## FAQs: 
**Why do we use sodium bicarbonate?**

A sodium bicarbonate (SoBi) buffer provides the optimal pH for the NHS ester of the dye to react efficiently with the antibody.

**Why do we exchange the buffer in gel filteration column?**

To be able to filter the sodium azide in protein solution. 

## Appendix
### Calculations for primary CD45 bioconjugation
| Material | Concentration | Amount | Concentration in mixture |
| -------- | ------- | ------- | ------- |
| Mouse Anti-Human CD45 | 3.3 µM | 20 µL | 2.7 µM  | 
| Atto 647N       | 1 mM   | 2 µL  | 83.3 µM | 
| SoBi            | 1 M    | 2 µL  | 8e+5 µM |

### Calculations for secondary bioconjugation
| Material | Concentration | Amount | Concentration in mixture |
| -------- | ------- | ------- | ------- |
| Goat Anti-Mouse | 3.3 µM | 50 µL | 2.7 µM  | 
| Atto 647N       | 1 mM   | 6 µL  | 98.3 µM | 
| SoBi            | 1 M    | 5 µL  | 8e+5 µM |

> [!NOTE]
> Concentration in mixture is calculated using: $$Concentration.in.mixture = \frac{Concentration*Amount}{Total Volume}$$
 
<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Feedback: [Create a pull request]()

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
