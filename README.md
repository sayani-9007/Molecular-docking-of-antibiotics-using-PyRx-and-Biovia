# Molecular Docking of Tetracycline with LasI (PDB: 1RO5)

## Overview

This project presents an in-silico molecular docking study of the antibiotic tetracycline against LasI (PDB ID: 1RO5), an AHL synthase from *Pseudomonas aeruginosa*.

The protein structure was obtained from the Protein Data Bank (PDB), and molecular docking was performed to investigate the potential binding of tetracycline within the LasI protein.

## Objective

The objective of this study was to investigate the potential interaction between tetracycline and LasI using molecular docking and to evaluate the predicted binding affinity and ligand–protein interactions.

## Target Protein

- **Protein:** AHL synthase LasI
- **Organism:** *Pseudomonas aeruginosa*
- **PDB ID:** 1RO5
- **Experimental method:** X-ray diffraction
- **Resolution:** 2.30 Å
- **Protein chain:** A
- **Structure source:** RCSB Protein Data Bank

The LasI structure contains a substrate-binding cleft and tunnel involved in its biological function. 

## Ligand

- **Ligand:** Tetracycline
- **Type:** Antibiotic
- **Docking study:** Tetracycline–LasI interaction

## Software and Tools

- BIOVIA Discovery Studio
- PyRx
- RCSB Protein Data Bank

## Methodology

### 1. Protein Structure Preparation

The crystal structure of LasI (PDB ID: 1RO5) was obtained from the Protein Data Bank.

Protein preparation was performed using BIOVIA Discovery Studio. The protein structure was inspected and prepared for molecular docking.

### 2. Ligand Preparation

The three-dimensional structure of tetracycline was obtained and prepared for docking.

The ligand structure was processed to obtain a suitable format for molecular docking using the selected docking workflow.

### 3. Molecular Docking

Molecular docking was performed using PyRx.

The prepared LasI protein was used as the receptor and tetracycline as the ligand. The docking search was performed within the selected binding region of the protein.

### 4. Interaction Analysis

The docked complex was further examined using BIOVIA Discovery Studio to visualize and analyze ligand–protein interactions.

The interactions were evaluated based on predicted binding pose and interactions such as:

- Hydrogen bonding
- Hydrophobic interactions
- Van der Waals interactions
- Other non-covalent interactions

## Results

### Docking Score

The predicted binding affinity obtained from PyRx/AutoDock Vina was:

**Binding affinity: -8.0 kcal/mol**

### Protein–Ligand Interactions

The docking pose showed interactions between tetracycline and residues within the selected binding region of LasI.

Important interacting residues identified using BIOVIA Discovery Studio:

- ARG70: Conventional hydrogen bond
- CYS68: Carbon hydrogen bond
- Several hydrophobic/alkyl interactions involving residues such as MET54, ILE107, LEU102, LEU128, PHE117, and VAL148
- Multiple van der Waals interactions with surrounding residues

### Visualization

The docked complex was visualized using BIOVIA Discovery Studio to examine the binding orientation and molecular interactions between tetracycline and LasI.

## Conclusion

This molecular docking study was performed to investigate the potential interaction of tetracycline with the LasI protein of *Pseudomonas aeruginosa*.

The docking results provide an in-silico assessment of the predicted binding affinity and interactions of tetracycline with LasI. Further experimental and computational studies would be required to validate the predicted interaction and determine its biological significance.

## Limitations

Molecular docking provides computational predictions and does not by itself establish biological activity or experimental binding.

The docking results should therefore be interpreted as preliminary in-silico findings.

## References

1. RCSB Protein Data Bank. PDB ID: 1RO5 – Crystal Structure of the AHL Synthase LasI.
2. Gould TA, Schweizer HP, Churchill ME. Structure of the *Pseudomonas aeruginosa* acyl-homoserine lactone synthase LasI. Molecular Microbiology. 2004;53:1135–1146.
