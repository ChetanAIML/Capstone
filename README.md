# Capstone : Human face detection


## Human_Face_Detection.ipynb 
This file contains logic of building custom models from scratch and training them on our choosen dataset.



  EDA : this section contains: loading of data, visualizing boxes of axes and cleaning the data.

  
  Helper Functions : this section contains the helper functions which are used across all over the notebook.
  
  
  Models : this section contains experimentals on different techniques to find out what model performs better.
  
  
  Predictions : this sections contains predictions from all the models to compare model performance.


## Human_Face_Detection_YOLOv8.ipynb 
This file contains logic to train a model to detect a human face from an image by leveraging the YOLOv8 Model

  Downloading Images: Download the dataset from Kaggle using opendatasets API

  Split Dataset: Split dataset into train, validation and test datasets. 
  
  Label File Creation: Create a "text" file with bounding box information for every image as per YOLOv8 requirements.

  Model Traning & Optimization: Train using the YOLOv8 pre-trained model using our dataset. Leverage Auto optimizer configuration

  Model Performance: Display nodel perforamce charts for Precision, Recall etc for Training and validation data. 

  Model Prediction: Predict image detection on random test dataset images and custom images for the model.
  



