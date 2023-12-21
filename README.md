# Brain-Tumor-Classifier
A convolutional neutral network that classifies if brain scans contain tumors.
## Summary
### Data Preprocessing
There was not a lot of data preproccessing that needed to be done, besides splitting the dataset into a training and testing sets. After implementing the model once, the model was very overfitted so data augmentation was added to create more variance in the model to reduce overfitting.
### The Model
The model that was used was a convolutional neutral network which is the standard model used for image classification. The model has 3 convolutional layers which all were followed by max pooling. Then were was a dropout layer which was followed by flattening to get the final result. After the data augmentation was done, the model had a validation accuary of 84%. The model was tested on 3 different images which all were classified correctly.
## Running the Program
1. Download the dataset from the Kaggle link.
2. Download the Python Notebook file.
3. If using Google Colab import the dataset into your google drive otherwise store the dataset on your computer.
4. Run the program.
