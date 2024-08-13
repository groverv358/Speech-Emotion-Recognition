## Speech Emotion Recognition

Speech Emotion Recognition, abbreviated as SER, is the act of attempting to recognize human emotion and affective states from speech. This is capitalizing on the fact that voice often reflects underlying emotion through tone and pitch. This is also the phenomenon that animals like dogs and horses employ to be able to understand human emotion.
\\
SER is tough because emotions are subjective and annotating audio is challenging.
\\
In this Python project, I have used the libraries librosa, soundfile, and sklearn (among others) to build a model using an MLPClassifier. This will be able to recognize emotion from sound files.First, I will load the data, extract features from it, then split the dataset into training and testing sets. Then, I will initialize an MLPClassifier and train the model and calculate the accuracy of our model.

