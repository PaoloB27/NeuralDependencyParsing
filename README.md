# Neural Transition-based Dependency Parsing

## Project description
The notebook contains the implementation of a neural parser for transition-based dependency parsing.
There two proposed implementations:
- Bi-LSTM to extract features from configurations and MLP to classify;
- pre-trained BERT for embedding the configuration words and MLP to choose the most probable transition.

## Results
The performances of the two models on the test set are the following:
- Bi-LSTM based model: UAS = [0.740, 0.770];
- BERT based model: UAS = [0.890, 0.900].
  Where we used UAS (i.e. Unlabeled Attachment Score) as evaluation metric.
