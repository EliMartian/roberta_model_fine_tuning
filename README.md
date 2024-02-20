# twitch_toxicity_detection
Fine tuning the RoBERTa model on a Kaggle toxicity subclassification data set to be applied to Twitch stream comments to classify them into different 
sub-categories of toxicity. Test and Train files not included as they exceed the size limit on Github. 

Kaggle Original Dataset: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data?select=train.csv 

Kaggle Test Set used: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data?select=test_public_expanded.csv

Twitch Dataset is a private resource of UWB otherwise would also be included.

Then, the resulting model is once again fine-tuned, but now on the union between another RoBERTa fine-tuned variant and Llama zero-shot labeling to further enhance toxic comment detection reliability. 

WARNING: the content in this could be considered vulgar and viewer discretion is advised. All comments are real toxic comments from users on a particular Twitch stream.
