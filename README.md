# EEE598_SML_project
Pytorch code for reproducing the results of our group project.

The main codes are in teh script folder. If you dont want to train, and just want to evaluate please use aae_pytorch_eval.py and change the checkpoint directory file to the desired prior('gaussian' or'bernoulli' or 'disc_unif'.
We have provided checkpoints for z_dim =10 for all of these three cases.
This script will run a KNN classifier, plot the confusion matrix and also plots retrieved images for query test images.



Requirements- 

PyTorch 1.0  with cuda and 

Torchvision

and usual Python ML libraries such as  

Scipy, Numpy, pandas

scikit-learn 

seaborn, matplotlib


