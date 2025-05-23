# ClassifyingChestXRays

The Chest X-ray image dataset can be found [here]([url](https://data.mendeley.com/datasets/rscbjbr9sj/2)).

In this project, I aimed to develop a neural network which could accurately predict whether the x-ray indicaed the patient was normal or had pneumonia. 

I started by loading relevant libraries and setting the basic configurations. I then set the training and validation data set. Because there was an uneven distribution of normal and pneumonia xray images in the training data set, I created class weights to penalize when the smaller group (normal) was misclassified. 

I then augmented the data so there was more deviation in the images and prevent a frail classification setting from forming. Then I built the model and made sure to include early stopping to prevent overfitting. Lastly, I went ahead and made the test dataset and then ran the model on the test dataset which resulted in a 90.71% classification accuracy. 

