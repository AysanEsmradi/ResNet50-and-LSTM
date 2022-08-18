# ResNet50-and-LSTM
The task is to implement of a temporal recognition network (e.g.,ResNet50+LSTM) to classify the surgical phase recognition.
There are 6 videos in the dataset( one file is for test), which are sampled from Cholec80. For each video, for training easily, we sample every 100 frames.
In the First file, ResNet50 is implemented to classify each frame.
In the Second file, ResNet50 is used to extract features for each frame and LSTM is used to capture temporal frames among three nearby frames.
Also, training and test loss curves and training and test accuracy curves are shown.
