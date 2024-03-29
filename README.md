# MNIST - Digit Recognizer

## Content of the project
This project (still a WIP) uses machine learning to identify digits from a dataset of tens of thousands of handwritten images. More details can be found in Kaggle's website: [https://www.kaggle.com/competitions/titanic](https://www.kaggle.com/competitions/digit-recognizer/data)


## Instructions
Three files are provided by Kaggle in the link provided above. They are:
- `train.csv` - the training set
- `test.csv` - the test set
- `sample_submission.csv` - a sample submission file in the correct format

The files contain gray-scale images of hand-drawn digits, from zero through nine. 

When running the code, make sure that the filepath for the several read_csv Panda functions have been updated correctly.


## Rationale and Methodology

### Data Exploration

### Feature Engineering

### Machine Learning Methodology

### Results and Discussion



## Usage

To run the analysis, open the `NLP_Disaster_Tweets.ipynb` notebook and execute each cell sequentially. Ensure that the required datasets are in the correct file paths.


## Dependencies

The following libraries are used in different parts of the project:
- Pandas
- Numpy
- Tensorflow
- Matplotlib.pyplot
- Seaborn
- Re
- String
- Keras_nlp
- Keras_core
- Symspellpy
- Spacy
- Os
- Sentence_transformers
- Sklearn.metrics
- Sklearn.metrics.pairwise


Proceed to their installation with the following code:

```
import numpy as np
import pandas as pd
import tensorflow as tf
import keras_core as keras
import keras_nlp
import seaborn as sns
import matplotlib.pyplot as plt
import re, string
from symspellpy import SymSpell, Verbosity
import spacy
import os
from sentence_transformers import SentenceTransformer
from sklearn.metrics.pairwise import cosine_similarity
from sklearn.metrics import ConfusionMatrixDisplay, confusion_matrix
```

## Installation
Ensure that you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/downloads/).


## Usage
You are allowed to view and fork the repository for personal use. If you have any questions or would like to discuss potential collaborations, feel free to reach out.


## Contributing
Although this project is not open-source, I welcome feedback, bug reports, and suggestions. If you encounter any issues or have ideas for improvements, feel free to send me an email to julian.enciso.izquierdo@gmail.com.


## License
This project is not open-source, and it does not come with a specific open-source license. All rights are reserved, and usage, modification, or distribution of the code is not permitted without explicit permission.

If you are interested in using or collaborating on this project, please send me an email to julian.enciso.izquierdo@gmail.com.


## Acknowledgments
Special thanks to Franck Jaotombo for his valuable feedback.
