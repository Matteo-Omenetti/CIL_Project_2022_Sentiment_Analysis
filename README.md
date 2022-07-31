# CIL_Project_2022_Sentiment_Analysis

## Running instruction

### Preprocessing


### Machine Learning method with TF-IDF
The notebook related to classical machine learning methods contains an SVM and a Random Forest applied on TF-IDF representations with all the executed cells. Rerunning the notebook requires the execution of the Preprocessing notebook. Furthermore, the following global variables have to be updated with the data and model paths on the local machine to make the notebook work properly.

```python
DATA_PATH = 'twitter-datasets/{}'
MODEL_PATH = 'models/{}'
```

There is even the option to execute the notebook without training by uploading pre-trained models and disabling the training parts by setting to False the following global variable.

```python
is_train_enabled = True
```

### W2V

### RNN
The notebook that was used to obtain the RNN results contains all executed cells. To rerun the notebook all the Preprocessing and W2V notebooks must have been executed before hand. Moreover the following references:

```python
DATA_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Dataset/{}'

# constants and global variables
PROBABILITIES = '/content/drive/MyDrive/Colab Notebooks/CIL/Probabilities /{}'
DATA_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Dataset/{}'
PREDICTIONS = '/content/drive/MyDrive/Colab Notebooks/CIL/Predictions/{}'
MODEL_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Models/{}'
```
Should be changed adequately to reflect the file path of the machine running the notbook.


### Bert 

### Transformers
