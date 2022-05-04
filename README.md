# Brain-tumor-detection
Brain tumor detection using CNN, ensemble learning techniques and data augmentation  
## Innovation Component
We are using extensive pre-processing techniques to eliminate all kinds of noises with several stages of filtering and thresholding. As the number of samples of Malignant tumors are limited we are going to increase the amount of data by synthesizing new data and this new data will be produced by slight modifications of already existing data, by performing this we will regularize our model thus reducing the overfitting problem and increasing accuracy. We have also proposed a novel Ensemble model with 5 weak learners which is outperforming every other model.
## Preprocessing Steps
1. Cropping
2. Resizing
3. Normalizing
4. Converting image to numpy array
5. Converting image data into a dataframe
6. Applying PCA to reduce the dimensions of the dataframe

## Models Used
* MLP classifier
* SVM classifier
* Decision Tree 
* Random Forest
* Logistic Regression
* XGB classifier
* CNN
* Ensemble learning model
## Results
Our proposed models are created using deep learning and machine learning techniques  which can predict whether an MRI scan is Malignant or Benign with accuracy more than 97% (In ensemble modeling) and less aligned to the limited set of data points so that we will be able to avoid overfitting.
The models we have specifically focussed are based on the research done by us on the best performing models with the high accuracy, and then we have provided a complete analysis of the models with tuned parameters.The models we used for analysis are CNN, Ensemble model, Random Forest, Decision Tree, and Multilayer Perceptron (MLP).
Ensemble model(SVM(with rbf kernel), Logistic Regression, XGB Classifier, MLP,SVM(with polynomial kernel)) is having the highest accuracy among all the models around 98.59%, followed by the CNN with 95.07% accuracy, Random Forest gave an accuracy of 76.76% and decision tree has 64.08% accuracy whereas MLP (with custom ANN configuration) gave accuracy of 89.43%.

