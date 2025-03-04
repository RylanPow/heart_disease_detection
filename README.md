# Heart Disease Detection
 
Data from the "Indicators of Heart Disease" data set on Kaggle
Data: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease?resource=download

Note: this repo orignally used data which turned out to be synthetically generated fake data completely dvoid of 
any actual signal or patterns.  This repo now trains the model on actual usable data.

# (DEPRECATED) note about the data: 
After having developed this model, it has come to my attention this data is synthetic and devoid of an actual signal. 
While quite unfortunate in a hilarious way, this was still not a terrible learning experience.

The current model, while lacking any predictive capability almost at all, is still a decent exercise in:\
-Pre-processing data(normalizing continuous labels and ordinal/one-hot encoding categorical features\
-hyper-parameter tuning and label selection\
-NN design in terms of neuron and label count as well as choice of activation\
-getting PyTorch to actually recognize my GPU
