# Application_CNN_MHT_problems
Code used for the thesis project: **Application of Convolutional Neural Networks in the Multiple Testing Problem**  for the in Master of Statistics in Data Science at Carlos III University of Madrid.

Notebook Chapter2_MHT contains all the code related to the **Chapter 2: MULTIPLE HYPOTHESIS TESTING**, specially the code related to the Simulation case 1 of the 
[femaleControlsPopulation](https://raw.githubusercontent.com/genomicsclass/dagdata/master/inst/extdata/femaleControlsPopulation.csv). At the end of this jupiter notebook, we have an extension of the models performance based on a CNN evaluation. Altough the methodology will be developed in Chapter 3, the notebook Chapter3_MICE_1000 contains the training of the model that then is loaded in the Chapter2_MHT file.

The notebook Chapter3_CNN contains all the coded of the **Chapter 3: CONVOLUTIONAL NEURAL NETWORKS** of the thesis. We continue the simulation of the Female mice diet with m = 100 features. For evaluation of the performance of the model for 20 iteration, we save the result in the object `report_AUPRC.pkl`.

The code related to the **Chapter 4-SIMULATION CASE 2: NORMAL POPULATIONS** is divided in two parts. First, we exclusively train the CNNs in the notebook Chapter4_1_Normal_Population. Then, we compare the performace of the CNN comparing with the BH procedure in the notebook Chapter_4_2_Normal_Population_Bench.


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/cconejov/Application_CNN_MHT_problems)





