# Strike

Content based recommendation system and website classifier.

It uses text data and URL scraped from website meta-tags to train a classification model and generate a similarity score of other websites within the dataset.

## Architecture
### Dataset and Data Cleaning
[Original dataset](https://www.kaggle.com/datasets/hetulmehta/website-classification)\
The original dataset contains website URL, website text and classification. A cleaner version of dataset is used to modify values.

### Classification Model
Text features are converted to vectors by implementing TF-IDF and passed to LinearSVC as training data.

### Data Extraction and Recommendation System
Website meta-data is extracted using BeautifulSoup and Cosine Similarity is used to find similarity score.

## Installation
This project requires Python and the following Python libraries installed:\
Pandas\
seaborn\
scikit-learn\
BeautifulSoup\
urllib.parse

You will also need to have software installed to run and execute a Jupyter Notebook.
