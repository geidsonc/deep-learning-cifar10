## Deep learning cifar10

Esse trabalho é resultado do uso de técnicas de deep learning utilizando a base de dados CIFAR10 para apresentação ao Curso de Ciência de Dados e Analytcs da Universidade Politécnica do Pernambuco

--------
This work is the result of the use of deep learning techniques using the CIFAR10 database for presentation to the Data Science and Analytcs Course at the Polytechnic University of Pernambuco.


### Techniques

- Simple VGG
- Data Augmentation (random flip, random rotation)
- Otimizer Adam and Adamax
- Growing Dropout
- Batch Normalization


### Models and results

| Model |  acc  |  acc_validation  |
|-------|-------|------------------|
| M1    | 30.52 |	36.04 |
| M2E3 	| 27.14 |	31.54 |
| M3E3Max | 	97.09 |	80.07 |
| M3E3Max + Drop V1 | 	91.88 |	82.58 |
| M3E3Max + Drop V2 |	85.71 |	84.18 |
| M3E3Max + augmentation V1 | 79.62 | 76.80 |
| M3E3Max + augmentation V2 |	85.65 |	81.30 |
| M3E3Max + Drop + augmentation 50 épocas |	76.21 |	79.24 |
| M3E3Max + Drop + augmentation 100 épocas | 	80.35 |	82.74 |
| M3E3Max + Drop + augmentation 100 épocas V2 |	83.17 |	84.18 |
| M4E4Max + Drop + augmentation 100 épocas | 	84.77 |	83.49 |
| M4E3Adam - Drop e augmentation 100 épocas  |	77.79 |	79.91 |
| M4E4Max + Drop + augmentation + BatchNorm 100 épocas |	89.07 |	87.42 |
