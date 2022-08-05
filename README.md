# EEG-Based-Emotion-Detection

- The project aimed to develop a deep learning model to identify human emotions using brain signals.

- We have used Convolutional Neural Network
(CNN), Sparse Autoencoder (SAE), and Deep Neural Network (DNN) in our model. The features extracted by the CNN are first sent to SAE for encoding
and decoding. Then the data with reduced redundancy are used as the input features
of a DNN for classification task. 

- A classification accuracy of 86% is obtained.

  Below is the general procedure followed.

![image](https://user-images.githubusercontent.com/103813206/182955738-22e5e195-8efb-4a0f-a888-fc4fb9a76654.png)

### Motivation of this project
- Possibility of falsely judging a person’s emotion through facial expressions.
- Since brain responses are used (EEG), accuracy will be higher.
- EEG is non invasive in nature.
- Helpful in recognizing the emotions of people with major disability, for better communication with them.


### Link to Dataset
https://www.eecs.qmul.ac.uk/mmv/datasets/deap/

### Link to Paper followed
https://www.frontiersin.org/articles/10.3389/fnsys.2020.00043/full


