# Paper-Geometrically-modulable-gait-design-for-Quadrupedal-robots

This is the code repository for the paper "Geometrically modulable gait design for Quadrupedal robots": <https://arxiv.org/abs/2308.14357>. This repository can generate the plots provided in the paper.

## Information on using this repository

Each ".mlx" file is a MATLAB livescript (analogous to a Python notebook) intended to be run sectionwise. 
1. Run the "se2_GenerQuad_TwoBeatGeometricMechanics.mlx" file to generate a geometric model for any nonslip two-beat gait cycle (not just trot as demonstrated in the paper). 
2. Next, Run the "se2_GenericQuad_TwoBeatSteerableTrot.mlx" for generating and visualizing two-beat quadrupedal gaits.
If you want to run just specific sections, use the data provided in the "Data" folder. If you uncomment lines corresponding to saving data in the livescript, the provided data will get overwritten. Hence, these lines are commented out by default.

For more details on the terminology and techniques, please refer to the paper linked above.
