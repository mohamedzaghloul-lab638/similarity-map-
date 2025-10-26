# similarity map
This project demonstrates how to use RDKit’s Similarity Map to visualize structural differences and similarities between two molecules — Salicylic acid (reference compound) and Aspirin (acetylsalicylic acid) (its derivative).

-Purpose of the Project

The goal of this mini-project is to visually and computationally compare a parent molecule and its modified derivative, to understand how chemical substitution affects molecular similarity and potentially biological activity.

Applications include:
Identifying conserved pharmacophore regions.
Visualizing structure–activity relationships (SAR).
Guiding rational drug design and molecular optimization.

- Molecules Used

Reference molecule (refmol): Salicylic acid
C1=CC=C(C(=C1)O)C(=O)O

Target molecule (mol): Aspirin (acetylsalicylic acid)
CC(=O)OC1=CC=CC=C1C(=O)O

- Output

Tanimoto Similarity Score:
Indicates how structurally similar the two molecules are (range: 0 to 1).
Example: Tanimoto = 0.76 → moderately high similarity.

Similarity Map Visualization:

Green regions → positive contribution to similarity.

Red regions → negative contribution (new or altered functional groups).
Example: the acetyl group in aspirin appears red, showing modification relative to salicylic acid.

- Interpretation

The salicylic acid core (benzene + carboxylic acid) contributes strongly to similarity.
The acetyl substitution on the phenolic OH decreases similarity slightly, visualized in red.
This illustrates how small chemical modifications alter molecular fingerprints and potential biological interactions.

Author

Mohamed Zaghloul
Chemistry Graduate | Computational Drug Design Enthusiast
