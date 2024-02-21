# Spotify Song Recommendation System 🎵

## Overview ℹ️

This project aims to build a song recommendation system using natural language processing techniques and cosine similarity on song lyrics. The system is built using Python, pandas, scikit-learn, and NLTK libraries. 🛠️

## Usage 🚀

1. **Data Preparation**:Load the dataset containing song information, including artist, song title, and lyrics. 📊

2. **Data Cleaning**: Clean the text data by converting it to lowercase and removing unwanted characters. 🔍

3. **Tokenization and Stemming**: Tokenize the lyrics and apply stemming using NLTK. 📝

4. **TF-IDF Vectorization**: Convert the tokenized lyrics into TF-IDF features. 📈

5. **Cosine Similarity**: Calculate cosine similarity between songs based on their TF-IDF vectors. 📐

6. **Song Recommendation**: Provide recommendations for similar songs based on a given song. 🎶

## Serialization 📁

The similarity matrix and DataFrame are serialized into binary files for later use. 💾

## Instructions on how to execute the files:
1. Download the dataset from this link [https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset/].<br>
2. Run the Commands that are in ModelTraining.ipynb in Anaconda Navigator and it will generate two binary files.<br>
3. Run the MRS.py file using command ‘streamlit run Recommend.py’ in terminal.

### GitHub Repository
The Python script used for analysis can be found in this [GitHub repository](ModelTraining.ipynb). Feel free to explore the script and dataset for further insights. 🔗

