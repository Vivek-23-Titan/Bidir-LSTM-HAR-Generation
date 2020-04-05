# Bidir-LSTM-HAR-Generation
Human Activity Generation and Recognition using Bidirectional LSTMs
This was my final year B.E. project wherein the dataset was from Wireless Sensor Data Mining Lab (WISDM). The objective of the project was to improve the classification accuracy of the dataset by introducing new generated data with the help of bidirectional Long-Short Term Memory(LSTM) networks. This model was first trained on the original dataset and was then used to predict the values of 6 different activities. These generated activities were compared with the original dataset activities and their losses were compared. For classification purpose, a convolution 1D activity classifier was built. This activity classifier was then trained on both the original dataset and the extended dataset, having generated activities. The results showed that the accuracy improved by expanding the dataset.
## Dataset
The data used for classification is provided by the Wireless Sensor Data Mining (WISDM) Lab and can be downloaded here. It consists of 1,098,207 examples of various physical activities (sampled at 20Hz) with 6 attributes: user,activity,timestamp,x-acceleration,y-acceleration,z-acceleration, and the activities include: Walking, Jogging, Upstairs, Downstairs, Sitting, Standing.

Original research done on this dataset can be found here.
