# General overview

After preprocessing used denoising autoencoder for feature engineering. The model was trained the simple neural network with 5 fold stratified cross validation model with focal loss, Wilcoxon Mann Whitney U statistic  and binary cross entropy with stochastic weight averaging and snapshot ensembling. The final predictions was the mean of the predictions of 3 models. 
