# Readme

# Datasets

**external** - folder that contains all scrapped data from internet

1. Indian Penal Code - .json [from website]
2. Code of Criminal Procedure - .json [from website]
3. Indian Constitution - .csv [from kaggle]

**train data** - from LegalEval cloud: [https://storage.googleapis.com/indianlegalbert/OPEN_SOURCED_FILES/ILDC-CJPE/trainData.zip](https://storage.googleapis.com/indianlegalbert/OPEN_SOURCED_FILES/ILDC-CJPE/trainData.zip)

**final data**: 

1. dataset without LDA analysis - [final_dataset_wo_lda.csv](https://mbzuaiac-my.sharepoint.com/:x:/g/personal/amirbek_djanibekov_mbzuai_ac_ae/EShRJNELI6xAjhxEDMWNrTgBQpv2484jBLEQiHP2zT2Cfg?e=39ypk5)
2. dataset with LDA analysis - [lda_final_dataset.csv](https://mbzuaiac-my.sharepoint.com/:x:/g/personal/amirbek_djanibekov_mbzuai_ac_ae/EXs0eiZDAKZOo0s5rY-oFyIB5KjdvsBVBMzudNAfXzQcRg?e=iFKNfc)

# Data Preprocessing

*constitution_embeddings.ipynb* 

- the process of working with constitution text

*data_preprocessing.ipynb*

 - the process of creating reference pairs, combination [data enrichment]

*doc2vec.ipynb* 

- the process of converting all text information to the vector form

*scraping_indian_articles.ipynb*

- the process of utilizing the code of using BeautifulSoup and related libraries to extract information from the web source pages

# Experiments

**deep-learning**

1. *deeplearning_with_LDA.ipynb*
    
    - in this notebook we tried to combine LDA topic analysis with RoBERTa transformer
    
    - Dataset’s PyTorch class with custom function of positional encoding.
    
2. *dnn_model.ipynb*
    
    - in this notebook we experimented with different DNN models: [BiLSTM, BiGRU, CNN]
    
    - relevant data preprocessing
    

**shallow-learning**

1. *shallow_learning_LDA_with_cosine.ipynb*
    
    - in this notebook we experimented with different Shallow Learning Algorithms: [Decision Tree, Extra Trees, XGBoost, Stacking, etc] (Pycaret)
    
    - text preprocessing for LDA analysis (Pycaret)
    
    - LDA analysis (Pycaret)
    

**major_voting.ipynb**

- simple grouping and metric calculation