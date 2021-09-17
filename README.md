# Application of Convolutional Neural Networks in Multiple hypothesis testing

This is the repository related to my thesis project: **Application of Convolutional Neural Networks in the Multiple Testing Problem**  for the Master of Statistics in Data Science at Carlos III University of Madrid.

<img src="https://github.com/cconejov/Application_CNN_MHT_problems/blob/main/tesis_image.PNG" title="Thesis" width="150" />


The language used is [Python][https://www.python.org/], especially the libraries [Pandas][https://pandas.pydata.org/], [NumPy][https://numpy.org/]-[SciPy][https://www.scipy.org/], and [scikit-learn][https://scikit-learn.org/stable/]. For training and calibrating the CNNs, we use the [Keras][https://keras.io/] API and [TensorFlow][https://www.tensorflow.org/]. All the code related to the simulation exercises is available in Jupiter notebooks using [Google Colaboratory][https://colab.research.google.com/notebooks/intro.ipynb]. All the code can be accesed

 If you want to check the code, it is easy =) with Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cconejov/Application_CNN_MHT_problems/)


Now, we give a brief description of all the related notebooks:

Notebook [Chapter2_MHT](https://colab.research.google.com/github/cconejov/Application_CNN_MHT_problems/blob/main/Chapter2_MHT.ipynb) contains all the code related to the **Chapter 2: MULTIPLE HYPOTHESIS TESTING**, especially the code related to Simulation case 1 of the 
[femaleControlsPopulation](https://raw.githubusercontent.com/genomicsclass/dagdata/master/inst/extdata/femaleControlsPopulation.csv). At the end of this Jupiter notebook, we have an extension of the model's performance based on a CNN evaluation. Although the methodology will be developed in Chapter 3, the notebook [Chapter3_MICE_1000](https://colab.research.google.com/github/cconejov/Application_CNN_MHT_problems/blob/main/Chapter3_Mice_1000.ipynb) contains the model's training that then is loaded in the `Chapter2_MHT` file.

The notebook [Chapter3_CNN](https://colab.research.google.com/github/cconejov/Application_CNN_MHT_problems/blob/main/Chapter3_CNN.ipynb) contains all the codes of the **Chapter 3: CONVOLUTIONAL NEURAL NETWORKS** of the thesis. We continue the simulation of the Female mice diet with m = 100 features. For the evaluation of the model's performance for 20 iterations, the evaluation time is considerably high; so, we save the result in the object `report_AUPRC.pkl`. 

The code related to the **Chapter 4-SIMULATION CASE 2: NORMAL POPULATIONS** is divided into two parts. First, we exclusively train the CNNs in the notebook [Chapter4_1_Normal_Population](https://colab.research.google.com/github/cconejov/Application_CNN_MHT_problems/blob/main/Chapter4_1_Normal_Population.ipynb). Then, we compare the performance of the CNN comparing with the BH procedure in the notebook [Chapter_4_2_Normal_Population_Bench](https://colab.research.google.com/github/cconejov/Application_CNN_MHT_problems/blob/main/Chapter4_2_Normal_Population_Bench.ipynb).
