# Human-Pose-Recognition-using-LSTM-LRCN-CNN

# LSTM (Long-Short Term Memory Network)

- LSTM CNN is a deep learning model that can be used for human pose recognition. LSTM is a type of recurrent neural network that is well-suited for modeling sequential data. CNN is a type of convolutional neural network that is well-suited for extracting features from images.
- LSTM is a type of recurrent neural network that is well-suited for modeling sequential data. Sequential data is data that is ordered in time, such as speech, music, and video. LSTM can learn long-term dependencies in sequential data, which makes it well-suited for tasks such as machine translation and speech recognition
- It works by maintaining a state that is updated over time. The state of the LSTM contains information about the past inputs to the network. This information is used to predict the next output of the network.
  
<img width="800" alt="Screenshot 2023-08-18 at 10 36 40 PM" src="https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/84bb058c-a4a9-427d-9dd8-db9f98f4188b">

# LSTM Trained Model

<img width="492" alt="Screenshot 2023-08-17 at 10 30 30 PM" src="https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/32b75ede-a67f-417a-808f-8559ae1cdc1f">

# LSTM Model Architecture 

![Structure of the model](https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/1146f37c-2b6c-44fb-bd52-5e82c6cc7e87)

# 1st Frame with the respective class of random video

![1st Frame ](https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/399e38c7-0e8e-489d-acd8-a1da5ec8b5db)


# LSTM Model Total Accuracy vs Total Validation

![totacc vs totval](https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/8f4461c9-fb2d-4ef1-8b3b-561946cbbd40)


# LSTM Model Total Loss vs Total Validation

![TotLoss vs TotVal](https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/cadff6f1-cd2a-48b3-a6b1-95d4a0ccbfc0)


# LRCN (Long-term Recurrent Convolutional Network)

- LRCN is a type of deep learning model that combines the strengths of LSTM and CNN. LSTM is a type of recurrent neural network that is well-suited for modeling sequential data. CNN is a type of convolutional neural network that is well-suited for extracting features from images.
- The LRCN model works by first extracting features from the image using a CNN. The extracted features are then fed into an LSTM, which models the temporal dependencies between the features. The output of the LSTM is then fed into a fully connected layer, which predicts the pose of the human body.


# LRCN Model

<img width="453" alt="Screenshot 2023-08-18 at 10 39 52 PM" src="https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/9a453faf-03d3-425c-8cf2-674dacdd4a24">

# LRCN Model Total Accuracy vs Total Validation

![lrcn totacc vs totval](https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/41b148e7-7a7e-46a6-8489-ebce3e84e75f)


# LRCN Model Total Loss vs Total Validation

![lrcn totloss vs totval](https://github.com/BaranidharanB/Human-Pose-Recognition-using-LSTM-CNN/assets/118863352/8431d9f9-1270-4583-b805-0e74f394aa6e)



# Reference 
- https://arxiv.org/abs/1411.4389
- https://medium.com/@tanmaychauhan111/human-activity-recognition-using-lstm-cnn-8ccb1a42cb81
  
