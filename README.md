Contents of SPE Hackathon 2023 data package:

Training + validation lines: SCAN001-011, SCAN024 and MRA036 - MRA040

Blind test line: SCAN025

Wells: Almere-01 (ALE-01), Blaricum-01-S1 (BLA-01-S1) and Landsmeer-01 (LSM-01), Heemskerk-01 (HEK-01), Q11-03, Westbeemster-02 (WBMS-02) and Westbeemster-03 (WBMS-03)

For these lines and wells we supply the following datatypes:

Target:
- Seismic inversion data (full package, all derived properties as well) – minus SCAN025, except angle stacks
- Seismic inversion reports – minus SCAN025 images

Input:
- Full stacks – all lines
- Offset/Angle stacks – all lines
- Velocities – all lines
- Processing reports – all lines
- Well logs
- Horizons TWT 3D and 2D



Mission, deliverables and criteria for judging the Hackathon submissions:

1) As a primary task, the contestants should be able to construct a neural network of choice that predicts acoustic impedance on the post-stack training, validation and full blind test line with highest possible accuracy and least possible misfit (loss), according to the judgment of the SPE experts.

2) As a secondary task, for each of the following inversion products properly predicted on the post-stack training, validation and full blind test line the contestants receive additional points: BulkModulus, Density, Permeability, PoissonsRatio, Porosity.

*) As a bonus task, the contestants are invited to construct an additional neural network of choice that predicts acoustic impedance and the other inversion products on the pre-stack angle-gather training, validation and full blind test line with highest possible accuracy and least possible misfit (loss), according to the judgment of the SPE experts. Additional inversion products that have training data and are to be predicted with the pre-stack AI solution are: ShearImpedance, ShearModulus, VpVsRatio, YoungsModulus

**) As an extra bonus task, points are earned with yet another additional neural network of choice that predicts successfully on the training, validation and full blind test line Facies and Horizons, as supplied with labels in the training data package.
