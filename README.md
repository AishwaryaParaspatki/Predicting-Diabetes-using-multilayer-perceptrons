# Predicting Diabetes using Multilayer Perceptrons

Technology stack:<br>
Python<br>
Keras - TensorFlow<br>
Matplotlib<br>
Numpy<br>
Seaborn<br>
sklearn<br>

I have used the Diabetes dataset hosted by Kaggle.<br>(https://www.kaggle.com/uciml/pima-indians-diabetes-database)

The datasets consist of several medical predictor (independent) variables and one target (dependent) variable, Outcome. Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.<br>
![Dataset](/images/Dataset_head.png)<br>
### Notebooks:<br>
Visualization.ipynb: This notebook consists of a study of the dataset using matplotlib and seabron libraries. <br>
![Histogram](/images/Histogram_data.png)
<br>
![Density graph](/images/Density_plot.png)
<br>
utils.ipynb: This notebook consists of the study of data before preprocessing and the preprocessing and feature engineering itself.<br>

main.ipynb: This notebook consists of the multilayer perceptron model with specifications as follows:
Sequential model with 3 layers: 1st layer - 32 hidden neurons with relu activation, 2nd layer - 16 hidden neurons with relu activation, output layer - 1 neuron with sigmoid activation. Adam optimizer with binary_crossentropy loss.<br>

### Evaluation metrics:<br>
1. Accuracy:<br>
![Accuracy](/images/Accuracy.PNG)<br>

2. Confusion Matrix:<br>
![Confusion Matrix](/images/Confusion_Matrix.png)<br>

3. ROC Curve:<br>
![ROC Curve](/images/ROC_curve.png)
