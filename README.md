# Capstone : Human face detection


## Human_Face_Detection.ipynb 
**This file contains logic of building custom models from scratch and training them on our choosen dataset.**


  &emsp;**EDA :** This section contains - loading of data, visualizing boxes of axes and cleaning the data.

  
  &emsp;**Helper Functions :** This section contains the helper functions which are used across all over the notebook.
  
  
  &emsp;**Models :** This section contains experimentals on different techniques to find out what model performs better.
  
  
  &emsp;**Predictions :** This sections contains predictions from all the models to compare model performance.


## Human_Face_Detection_YOLOv8.ipynb 
**This file contains logic to train a model to detect a human face from an image by leveraging the YOLOv8 Model**

  &emsp;**Downloading Images:** Download the dataset from Kaggle using opendatasets API

  &emsp;**Split Dataset:** Split dataset into train, validation and test datasets. 
  
  &emsp;**Label File Creation:** Create a "text" file with bounding box information for every image as per YOLOv8 requirements.

  &emsp;**Model Traning & Optimization:** Train using the YOLOv8 pre-trained model using our dataset. Leverage Auto optimizer configuration

  &emsp;**Model Performance:** Display nodel perforamce charts for Precision, Recall etc for Training and validation data. 

  &emsp;**Model Prediction:** Predict image detection on random test dataset images and custom images for the model.
  



