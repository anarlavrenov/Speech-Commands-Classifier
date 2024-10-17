# Speech-Commands-Classifier
This repository showcases the training and inference processes. The model was trained on torchaudio dataset https://pytorch.org/audio/stable/generated/torchaudio.datasets.SPEECHCOMMANDS.html#torchaudio.datasets.SPEECHCOMMANDS. This dataset contains around 100k records and 35 classes. The model is increadibly small - contains aroung 600k parameters and weights 2.5 MB but still shows decent resuls: 91% accuracy on validation dataset and 88% on test dataset.

The model itself is also attached at the repo. You can try the model itself by going to inference.ipynb, speak out the words via microphone and see classification.
