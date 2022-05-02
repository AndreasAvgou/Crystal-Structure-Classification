# Crystal Structure Classification

![image](https://user-images.githubusercontent.com/22665704/166236755-ccf1ed8c-0abb-4fa5-9bbd-b177c6c19e26.png)

## Problem Statement

There have been numerous studies of perovskite structures in the field of ceramic science and engineering, materials physics, and solid-state inorganic chemistry owing to their compositional flexibility, distortion of the cation configuration, and mixed valence state electronic structure. 
This has prompted scientists to tune the material’s properties so as to obtain a much more ideal perovskite structure. An ideal perovskite has an ABX3 structure where A and B are two differently sized cations, and X is an anion
A total of 73 elements have been identified in the A and B sites of ABO3 structures, leading to numerous oxides of the perovskite type. Features such as electronegativity, ionic radius, valence, and bond lengths of A-O and B-O pairs have been identified that enable a priori crystal structure prediction.

## Object

Our object was to classify the perovskite oxides based on their characteristics

## Data Description

The data consists of 4,165 ABO3 perovskite-type oxides. Each observation is described by 13 feature columns and 1 class column which identifies it to be either a cubic, tetragonal, orthorhombic, and rhombohedral structure.

```
1) v(A) - Valence of A

2) v(B) - Valence of B 

3) Radius A (r(A)) - ionic radius of A cation

4) Radius B (r(B)) - ionic radius of B cation

5) Electronegativity of A (EN(A)) - Average electronegativity value of A cation

6) Electronegativity of B (EN(B)) - Average electronegativity value of B cation

7) l(A-O) - Bond length of A-O pair

8) l(B-O) - Bond length of B-O pair

9) ΔENR - Electronegativity difference with radius

10) tG - Goldschmidt tolerance factor

11) τ - New tolerance factor 

12) Μ - Octahedral factor
```
## Dataset

You can find the dataset that was used in this [link](https://drive.google.com/drive/folders/1w3hLEJZ1TFPvQ6KDgbR3iDJOt5FWUja2?usp=sharing)
