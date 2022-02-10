# _IN SITU_ HI-C STEP 03: DNA SHEARING & SIZE SELECTION
---
## LAB INSTRUTIONS
---
### DNA SHEARING 

1) Cool tubes at room temperature.
2) Split into two 750μl aliquots in 2ml tubes and add 1.6X volumes of pure ethanol and 0.1X volumes of 3M sodium acetate, pH 5.2, to each tube. 
3) Mix by inverting and incubate at -80°C for 15 minutes.
4) Centrifuge at max speed, 2°C for 15 minutes. Keep the tubes on ice after spinning and carefully remove the supernatant by pipetting.
5) Resuspend, combining the two aliquots, in 800μl of 70% ethanol. Centrifuge at max speed for 5 minutes.
6) Remove all supernatant and wash the pellet once more with 800μl of 70% ethanol.
7) Dissolve the pellet in 130μl of 1X Tris buffer (10 mM Tris-HCl, pH 8) and incubate at 37°C for 15 minutes to fully dissolve the DNA.
8) To make the biotinylated DNA suitable for high-throughput sequencing using Illumina sequencers, shear to a size of 300-500bp using the following parameters:
- Instrument: Covaris LE220 (Covaris, Woburn, MA)
    - Volume of Library: 130μl in a Covaris microTUBE
    - Fill Level: 10
    - Duty Cycle: 15
    - PIP: 500
    - Cycles/Burst: 200
    - Time: 58 seconds

9) Transfer sheared DNA to a fresh 1.5ml tube. 
10) Wash the Covaris vial with 70μl of water and add to the sample,bringing the total reaction volume to 200μl.
11) Run a 1:5 dilution of DNA on a 2% agarose gel to verify successful shearing. 
- _Note: For libraries containing fewer than 2x106 cells, the size selection using AMPure XP beads described in the next steps could be performed on final amplicons rather than before biotin pull-down._

### SIZE SELECTION

12) Warm a bottle of AMPure XP beads (Beckman Coulter, A63881) to room temperature. 
- _Note: To increase yield, AMPure XP beads can be concentrated by removing some of the clear solution before the beads are mixed for use in the next steps._

13) Add exactly 110μl (0.55X volumes) of beads to the reaction. Mix well by pipetting and incubate at room temperature for 5 minutes.
14) Separate on a magnet. Transfer the clear solution to a fresh tube, avoiding any beads. The supernatant will contain fragments shorter than 500bp.
15) Add exactly 30μl of fresh AMPure XP beads to the solution. Mix by pipetting and incubate at room temperature for 5 minutes.
16) Separate on a magnet and keep the beads. Fragments in the range of 300-500bp will be retained on the beads. Discard the supernatant containing degraded RNA and short DNA fragments.
17) Keeping the beads on the magnet, wash twice with 700μl of 70% ethanol without mixing.
18) Leave the beads on the magnet for 5 minutes to allow remaining ethanol to evaporate.
19) To elute DNA, add 300μl of 1X Tris buffer, gently mix by pipetting, incubate at room temperature for 5minutes.
20) Separate on a magnet, and transfer the solution to a fresh 1.5ml tube.
21) Quantify DNA by Qubit dsDNA High Sensitivity Assay (Life Technologies, Q32854) and run undiluted DNA on a 2% agarose gel to verify successful size selection.
---
## CITATIONS

This protocol was adapted from:

[Rao, S. S. P., M. H. Huntley, N. C. Durand, E. K. Stamenova, I. D. Bochkov, J. T. Robinson, A. L. Sanborn, I. Machol, A. D. Omer, E. S. Lander, and E. L. Aiden. 2014. A 3D Map of the Human Genome at Kilobase Resolution Reveals Principles of Chromatin Looping. Cell 159:1665–1680.](https://www.sciencedirect.com/science/article/pii/S0092867414014974)


