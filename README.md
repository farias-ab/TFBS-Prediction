# Predicting Bacterial Transcription Factor Binding Sites Through Machine Learning and Structural Characterization Based on DNA Duplex Stability

André Borges Farias (1,2), Gustavo Sganzerla Martinez (3), Edgardo Galán-Vásquez (4), Marisa Fabiana Nicolás (1) and Ernesto Pérez-Rueda (2)

1. Laboratório Nacional de Computação Cientı́fica - LNCC, Avenida Getúlio Vargas, 25651075, Rio de Janeiro, Brazil, 2. Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas, Universidad Nacional Autónoma de México, Unidad Académica del Estado de Yucatán, Carretera Sierra Papacal, 97302, Yucatán, México, 3. Microbiology and Immunology, Dalhousie University, 5850 College Street, B3H 4H7, Nova Scotia, Canada and 4. Departamento de Ingenierı́a de Sistemas Computacionales y Automatización, Instituto de Investigaciones en Matemáticas Aplicadas y en Sistemas, Universidad Nacional Autónoma de México, Ciudad Universitaria, Circuito Escolar S/N, 01000, Mexico City, México
∗ Corresponding author. ernesto.perez@iimas.unam.mx, bfarias.andre@gmail.com

---

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Model Information](#model-information)
7. [Results](#results)
8. [Contributors](#contributors)
9. [License](#license)

---

### Introduction

Transcriptional factors (TFs) in bacteria play a crucial role in gene regulation by binding to specific DNA sequences, thereby assisting in the activation or repression of genes. Despite their central role, deciphering shape recognition of bacterial TFs-DNA interactions remains an intricate challenge. A deeper understanding of DNA secondary structures could greatly enhance our knowledge of how TFs recognize and interact with DNA, thereby elucidating their biological function. In this study, we employed machine learning algorithms to predict transcription factor binding sites (TFBS) and classify them as directed-repeat (DR) or inverted-repeat (IR). To accomplish this, we divided the set of TFBS nucleotide sequences by size, ranging from 8 to 20 base pairs, and converted them into thermodynamic data known as DNA Duplex Stability (DDS). Our results demonstrate that the Random Forest algorithm accurately predicts TFBS with an average accuracy of over 82% and effectively distinguishes between IR and DR with an accuracy of 89%. Interestingly, upon converting the base pairs of several TFBS-IR into DDS values, we observed a symmetric profile typical of the palindromic structure associated with these architectures. This study presents a novel TFBS prediction model based on a DDS characteristic that may indicate how respective proteins interact with base pairs, thus providing insights into molecular mechanisms underlying bacterial TFs-DNA interaction.

### Requirements

- Python 3.x
- Pandas
- Scikit-learn
- Pickle
- Jupyter Notebook

### Installation

To install and set up the project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository.git
