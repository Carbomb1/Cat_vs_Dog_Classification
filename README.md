# Cat_vs_Dog_Classification

![image](https://user-images.githubusercontent.com/45641348/168451763-defd7e7f-2be5-4ba3-8249-f361f0a56fb1.png)


## Background
This project follows the work I did for a Kaggle competition where users try to predict how probable an image is to being a cat or a dog. The final score on a loss function, with 0.0 being a perfect score. \
Kaggle competition link -https://www.kaggle.com/competitions/dogs-vs-cats-redux-kernels-edition/overview

## Main Strategies Used

### Using Generators to Store Image Data
To store the image data I used the Image Data Generators in the Keras package. This allowed me to streamline my file processing, and allowed for hyperparameters to slighly change the format of the images. 

### Final Model
The final model that I used in this competition was a Convolutional Neural Network (CNN) that used the prebuilt Xception infastructure. I found a SGD optiimizer with momentum to achieve the best results. 


## Results
In my final results file I was able to achieve an loss of 0.07816. With the best official loss being 0.03302.

![image](https://user-images.githubusercontent.com/45641348/168451611-86d097ca-a81a-4878-bdc1-babffde8fb75.png)

## Contents of Repository

### Code File
The Cat_vs_Dog_Classification.ipynb file shows the detailed steps to arrive at the final predictions. The file was written using Python through a Google Colab notebook.

### Submission File 
The Cat_Dog_Submission_File.csv contains the final predictions that were uploaded to the Kaggle competition. 

