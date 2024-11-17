# AT&T HACKATHON 2024 - OPEN DATASETS, MODEL TRAINING, DATA ANALYSIS

Please, keep in mind that these are just our recommendations and tips. You are free to use whatever technologies and tools you want.

## Load dataset, train a model

In our workshop, we are working with Jupyter notebooks instead of Python files. Notebook is a file consisting of cells (code cells and text cells), which you can run separately instead of running the whole code. This is very convenient for development. Of course, feel free to use traditional Python files.

### Option 1: Google Colab

Colab is a hosted Jupyter Notebook service that requires no setup to use and provides free access to computing resources, including GPUs and TPUs. You can log in with your Google account, free version should be enough for easier use-cases.

### Option 2: Your own device

Create a virtual environment:
`python3 -m venv venvName`

Activate your virtual environment:
`source venvName/bin/activate`

Install Python packages:
`pip install -r requirements.txt`


### Option 3: Azure

Azure has a free trial for 30 days/200 USD. You can register with your GitHub or Microsoft account.
For GPU access, you need to request quota increase. For request quota increase, you need to select resource provider. The process is a bit complicated, so if you wanna use it, prepare it in advance.

You can check this official guide:
https://learn.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources?view=azureml-api-2


## Useful websites

We came up with a list of websites and resources you may find useful.

### Datasets

- https://www.kaggle.com/datasets
- https://datasetsearch.research.google.com/
- https://apps.who.int/gho/data/node.home - Global Health Observatory data repository - useful for health & lifestyle topic
- https://data.brno.cz/

### Python packages

- Pandas (Python Data Analysis Library) - great way to load a dataset and work with it, Pandas can do some magic, gives you basic statistics data about your dataset etc.
- Tensorflow - ML and AI library
- PyTorch - ML and AI library, said to be better for making complex custom models, research etc.
- Scikit-learn - contains a lot of useful tools (like splitting data to test/train, scaling data) and some basic models 

### Concepts worth studying

If you wanna take ML seriously, you should be interested in these topics:
- Overfitting/underfitting and techniques how to prevent it
- Data preprocessing
- Different metrics (accuracy is good, but sometimes not enough - check precision/recall)

## BONUS: Some ideas for your projects
- You don't need to train a model. Sometimes, it is worth just to display dataset in some interesting way. You may try to use techniques like clustering.
- You can also work with dataset, and use it in some interactive web app, which will help people to understand that data.


