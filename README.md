# UCF_101_ActionRecognition
The dataset can be downloaded from the following link: https://www.crcv.ucf.edu/data/UCF101.php 
## 1.Data Processing:
  - A subset of 40 classes from the entire dataset is used for the task of action recognition
  - The data is converted into dataframes which could be used for the DL model
  - Two samples and their captions are plotted for reference
  - After preprocessing the data is splitted into train and validation data for training
## 2.Model Building:
  - VGG19 as CNN encoder is used for feature extraction
  - Added 2-layer LSTM model and other relevant layers as decoder
  - dropout layer is added
  - model summary is printed
## 3.Model Compilation:
  Model is compiled with appropriate optimizer, learning rate, loss function and any other hyper parameter
## 4.Model Training:
  - The model is trained with appropriate number of epochs
  - The train and validation loss for each epoch is printe
  - The loss and accuracy history graphs for both train and validation set is plotted
## 5.Model Evaluation:
  - 5 random data from the test set is taken and performed Expression recognition
  - confusion metrics and classification report is printed for the test data.
