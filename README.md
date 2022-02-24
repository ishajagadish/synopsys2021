# synopsys2021
Project Title: A Multistep, ML-Based Predictor of Parkinson's Disease Progression Using
GWAS, Patient Symptoms and Gene Expression Data

Predicting Parkinson's Disease (PD) susceptibility involves three different approaches: using
known genetic variants and patient genotypes, RNA sequencing, and measuring disease
symptoms. The first approach works for predicting familial cases but not idiopathic, which
requires all three approaches for every patient, incurring unnecessary cost and patient
inconvenience. My goal was to develop a novel, neural network-based PD-predictor software for
healthcare practitioners that combines all approaches into three adaptive steps to best predict a
patient's PD stage. Enhanced prediction in each successive step is based on patient genotype,
RNA-sequencing, and symptoms, respectively. Only if it exceeds a certain threshold can the
patient proceed to subsequent steps. I used Google Colab to design and train the models. I
started with the publicly available patient genotype, gene expression, and symptoms data from
PPMI. I prepared the training dataset using one-hot encoding and quantile binning, and built a
deep neural network model for each step. Next, I trained and fine-tuned each model for optimal
accuracy. Finally, I deployed the models onto a web application with a UI. I tested each of the
three models with many new patient samples. The first step correctly predicted patients' PD
susceptibility with greater than 95% accuracy. The later models correctly predicted their PD
stage with more than 80% accuracy. Using patient gait data and a current neural network would
further improve accuracy. The software's unique adaptive feature selectively validates patients'
PD susceptibility, eliminating unnecessary testing. This breakthrough technique provides a
low-cost, highly effective tool for early PD detection.
