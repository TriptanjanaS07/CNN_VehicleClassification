# CNN_Vehicle Classification

This project uses CNN to classify if the image is either of a bike or a car. The model is trained on a custom dataset and can accurately detect bikes and cars in various settings.

# Dataset

The dataset consists of 132 images which are divided into test and train folders.The test folder contains 15 images each of bike and car.The train folder contains 51 images each of bike and car.Training data is the set of the data on which the actual training takes place. Validation split helps to improve the model performance by fine-tuning the model after each epoch.

# Steps to run the code

1. Load the 'Bike_and_Car_CNN.ipynb' in the google collab.

2. Connect the collab to a runtime and change the runtime type to GPU. (runtime -> runtime type ->hardware acclerator -> GPU)

3. Upload the Bike and cars.zip to the collab either using drag and drop or by uploading it to your drive and connecting the drive to the notebook.

4. Unzip the file using the command
```bash 
!unzip '/path to/Bike and cars.zip'
```

5. Copy the path of train and test folder and paste it in the respective section of directory.
<img src="https://github.com/TriptanjanaS07/CNN_VehicleClassification/blob/main/CNN%20Readme%20Images/Screenshot%202023-04-25%20at%202.22.48%20PM.png" style=""></img>

6. Go to Runtime -> Run all or press ctrl+F9

7.
