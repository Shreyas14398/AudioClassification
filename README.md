# AudioClassification of Environmental sounds using Deep Learning

> Our First Machine Learning Model

## Dependencies required

- Python 2.7 (3.6 not tested)
- librosa
- tensorflow
- pysoundfile
- matplotlib
- scikit-learn- numpy
- keras

## Dataset

Dataset can be downloaded at [Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/YDEPUT) or [Github](https://github.com/karoldvl/ESC-50).

We'd recommend use ESC-10 for the sake of convenience.

## Feature Extraction
Copy the datasets under `data` directory and run :

$ python feat_extract.py

Features extraction will be completed.

## Classify with Multilayer Perception

Run `nn.py` to train and test the network.

## Classify with SVM

Run `svm.py` to see the result.

## Classify with Convolutional Neural Network

Run `cnn.py` to train and test the model.



