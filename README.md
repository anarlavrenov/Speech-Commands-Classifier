# Speech-Commands-Classifier

This repository demonstrates both the training and inference processes of a neural network model developed using the Speech Commands dataset from torchaudio: [SpeechCommands Dataset](https://pytorch.org/audio/stable/generated/torchaudio.datasets.SPEECHCOMMANDS.html#torchaudio.datasets.SPEECHCOMMANDS). The dataset consists of approximately 100,000 recordings across 35 different classes.

The model is impressively compact, containing around 600,000 parameters and weighing only 2.5 MB, yet it delivers solid performance—achieving 91% accuracy on the validation set and 88% on the test set.

The trained model is also included in the repository. You can try it out by running the `inference.ipynb` notebook, speaking the commands via your microphone, and seeing the classification results.
