# TensorFlow-DeepLearning_2020
Files, code and presentation used in the OpenCampus curse "Machine Learning With TensorFlow" and "Deep Learning"

The project was to create a Deep-Neural-Network and/or a Convolutional-Neural-Network to predict DNA binding of the plant specific transcription factor BPC6. 
For training the Chip experiment from :

Role of BASIC PENTACYSTEINE transcription factors in a subset of cytokinin signaling responses
Carly M. Shanks  Andreas Hecker  Chia‐Yi Cheng  Luise Brand  Silvio Collani  Markus Schmid  G. Eric Schaller  Dierk Wanke  Klaus Harter  Joseph J. Kieber
First published: 15 May 2018 https://doi.org/10.1111/tpj.13962

The betgraph files were transformed into numpy arrays representing a binding value (number of chip-seq-reads) for each position in the genome. 
The Tair10 Arabidopsis thaliana genome sequence One-Hot-End encoded based on the skip used here: 

https://www.kaggle.com/thomasnelson/working-with-dna-sequence-data-for-ml
Working with DNA sequence data for ML
Python notebook using data from example-fasta ·

and used as input for the NN.
