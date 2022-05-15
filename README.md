# Sign Language Detection

In this project Deep Learning is used to recognise and classify different actions. </br></br>
1. First, we use mediapipe to dectect various keypoints from our faces and hands.</br>
2. We collect the dataset using these keypoints for the actions and store them as an array.</br>
3. The dataset is then given to an LSTM model to learn the actions.</br>
4. We use an LSTM model as we want to detect the actions from a set of frames rather than a single frame.</br>
5. Finally we use our camera for real time testing.</br>
