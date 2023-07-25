# UCF_101_ActionRecognition
The dataset can be downloaded from the following link: https://www.crcv.ucf.edu/data/UCF101.php 
1.	Data Processing:
     	a.A subset of 40 classes from the entire dataset is used for the task of action recognition.
  	  b.The data is converted into dataframes which could be used for the DL model.
  	  c.Two samples and their captions are plotted for reference.
      d.After preprocessing the data is splitted into train and validation data for training.
2.	Model Building:
    	a.VGG19 as CNN encoder is used for feature extraction.
  	  b.2-layer LSTM model and other relevant layers as decoder.
  	  c.dropout layer is added.
  	  d.model summary is printed
3.	Model Compilation:
	    a.Model is compiled with appropriate optimizer, learning rate, loss function and any other hyper parameter
4.	Model Training:
  	  a.The model is trained with appropriate number of epochs.
  	  b.The train and validation loss for each epoch is printed.
  	  c.The loss and accuracy history graphs for both train and validation set is plotted.
5.	Model Evaluation:
      a.5 random data from the test set is taken and performed Expression recognition.
  	  b.confusion metrics and classification report is printed for the test data.
