## Video Recognition on UCF50 Dataset using CNN-LSTM
This Repository demonstrates video recognition using a Convolutional Long Short-Term Memory (CNN-LSTM) model on the UCF50 dataset. The goal is to classify videos into different action categories.
### Model Architecture
**CNN-LSTM**

A CNN-LSTM model combines Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks. CNNs are used to extract spatial features from video frames, while LSTMs capture temporal dependencies. This architecture is effective for tasks involving spatiotemporal data, such as video recognition and action classification.

**Applications of CNN-LSTM:**
* **Video Classification:** Recognizing actions or events in video sequences.
* **Human Activity Recognition:** Identifying activities from video data, useful in surveillance and healthcare.
* **Gesture Recognition:** Interpreting gestures in video streams for human-computer interaction.

### Dataset
The UCF50 dataset consists of 50 action categories and is widely used for action recognition tasks. Each category contains a collection of videos showing various actions. For more details, 
refer https://www.crcv.ucf.edu/data/UCF50.

Download the UCF50 dataset from the following URL:
* https://www.crcv.ucf.edu/data/UCF50.rar
  
### Code Highlights
* **Frame Extraction:** Extract and preprocess frames from videos.
* **Dataset Creation:** Assemble features and labels for training and testing.
* **Model Definition:** Build and compile the CNN-LSTM model.
* **Training:** Train the model with early stopping to prevent overfitting.
* **Evaluation:** Evaluate the model on the test set and visualize performance.

### References
* https://medium.com/@jaykumaran2217/action-recognition-ucf101-using-lstm-and-cnn-cnn-lstm-ef3e55075f90
* [[CNN-LSTM Networks](https://www.youtube.com/watch?v=QmtSkq3DYko)](https://youtu.be/QmtSkq3DYko?si=Y3frChrKFD7S1hr8)
