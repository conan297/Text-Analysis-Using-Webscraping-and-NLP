This repository contains a Jupyter notebook for text analysis. The notebook performs various text analysis tasks, including data loading and preprocessing, exploratory data analysis, text vectorization, topic modeling, and sentiment analysis.


Overview
The text_analysis.ipynb notebook uses Python 3.7 and the following libraries:


pandas
numpy
matplotlib
seaborn
nltk
gensim
sklearn
The notebook uses a sample dataset of text documents, which is not included in the repository. Users must provide their own dataset in CSV format, with one column containing the text documents and another column containing the document labels.


Running the notebook
To run the text_analysis.ipynb notebook, follow these steps:

Install the required libraries by running the following command in your terminal or command prompt:

pip install pandas numpy matplotlib seaborn nltk gensim sklearn
Download the text_analysis.ipynb notebook and save it to a local directory.
Open the notebook in Jupyter Notebook or Jupyter Lab.
Run the cells in order, starting from the top.
Note: Some cells may take a few minutes to run, depending on the size of the dataset and the computational resources available.


Data
The text_analysis.ipynb notebook uses a sample dataset of text documents. The dataset is not included in the notebook and must be provided by the user. The dataset should be in CSV format, with one column containing the text documents and another column containing the document labels.


To use your own dataset, replace the data.csv filename in the load_data function with the path to your dataset.


Code
The text_analysis.ipynb notebook contains the following code:

load_data: Loads the dataset and performs basic preprocessing.
exploratory_data_analysis: Performs exploratory data analysis on the dataset.
text_vectorization: Vectorizes the text documents using TF-IDF.
topic_modeling: Performs topic modeling using Latent Dirichlet Allocation (LDA).
sentiment_analysis: Performs sentiment analysis using the VADER algorithm.
Output
The text_analysis.ipynb notebook produces the following output:

Data loading and preprocessing: A preprocessed dataset.
Exploratory data analysis: Plots and statistics describing the dataset.
Text vectorization: A matrix of TF-IDF vectors.
Topic modeling: A list of topics and their corresponding word distributions.
Sentiment analysis: A sentiment score for each text document.

