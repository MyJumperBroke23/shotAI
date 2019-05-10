# Introduction
This project attempts to use a time-series LSTM to predict made/missed freethrows using Pose Keypoint Data

# The Actual Model
This repository only contains the dataset, the link to the the model can be found here:  

[shotLSTM.ipynb](https://colab.research.google.com/drive/1jwINMrLyAQtpnAfK4jA9I74QyWx9z14r)

# Using this model with your own data
If you want to generate your own data, you can run OpenPose fairly quickly using Google Colab's free GPU.  

A ipynb that runs OpenPose on google drive files can be found [here](https://colab.research.google.com/drive/1FAm8odwIkumOy8vt1pu8Qc9dEYUeKVO7)

If you want the LSTM model to work as is, format the resultant keypoint folders as:  
  
"(made/missed)(number)keypoints" i.e. made1keypoints or missed10keypoints

Place all resultant folders into respective class folders titled "madeKeypoints" and "missedKeypoints" 

# Pretrained models
As of now, there are no pretrained models, but they will hopefully be added in the near future
