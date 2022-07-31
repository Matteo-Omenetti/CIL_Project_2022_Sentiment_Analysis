# CIL_Project_2022_Sentiment_Analysis

## Running instruction

### Preprocessing
Run all the cells twice. Once with the following flag set to True and once to False:

```python
is_bert_preprocessing_enabled = True
```

### Machine Learning method with TF-IDF
The notebook related to classical machine learning methods contains an SVM and a Random Forest applied on TF-IDF representations with all the executed cells. Rerunning the notebook requires the execution of the Preprocessing notebook. Furthermore, the following global variables have to be updated with the data and model paths on the local machine to make the notebook work properly:

```python
DATA_PATH = 'twitter-datasets/{}'
MODEL_PATH = 'models/{}'
```

There is even the option to execute the notebook without training by loading pre-trained models and disabling the training parts by setting to False the following global variable:

```python
is_train_enabled = True
```

### W2V

The notebook that was used to obtain the W2V + MLP results contains all executed cells. To rerun the notebook  the Preprocessing must have been executed before hand. Moreover the following references:

```python
DATA_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Dataset/{}'

# constants and global variables
PROBABILITIES = '/content/drive/MyDrive/Colab Notebooks/CIL/Probabilities /{}'
DATA_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Dataset/{}'
PREDICTIONS = '/content/drive/MyDrive/Colab Notebooks/CIL/Predictions/{}'
MODEL_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Models/{}'
```
Should be changed adequately to reflect the file path of the machine running the notebook.

There is even the option to execute the notebook without training by loading pre-trained models and disabling the training parts by setting to False the following global variable:

```python
is_train_enabled = True
is_w2v_train_enabled = True
```

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
Should be changed adequately to reflect the file path of the machine running the notebook.


### Transformers
The notebook that was used to obtain the Transformers results contains all executed cells. To rerun the notebook the Preprocessing notebook must have been executed before hand. Moreover the following references:

```python
DATA_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Dataset/{}'

# constants and global variables
PROBABILITIES = '/content/drive/MyDrive/Colab Notebooks/CIL/Probabilities /{}'
DATA_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Dataset/{}'
PREDICTIONS = '/content/drive/MyDrive/Colab Notebooks/CIL/Predictions/{}'
MODEL_PATH = '/content/drive/MyDrive/Colab Notebooks/CIL/Models/{}'
```
Should be changed adequately to reflect the file path of the machine running the notebook.

There is even the option to execute the notebook without training by loading pre-trained models and disabling the training parts by setting to False the following global variable:

```python
is_train_enabled = True
```

### TransformerLogReg
The folder contains Jupyter notebook files following the order to reproduce the result.
1. Reprocessing data, split data function. [Data](https://drive.google.com/drive/folders/11-7K9zOfxZUY7-fAabRZjjMyutwywGXb?usp=sharing) can be downloaded here.
2. Train and predict with Transformers + Huggingface implimented with Pytorch.
3. Fine-tuning Logistic Regression function and predict the final predictions.
