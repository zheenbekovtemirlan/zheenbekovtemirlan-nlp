
---

# ChatGPT Prompts NLP Analysis

This project explores a dataset of ChatGPT prompts, applying various natural language processing (NLP) techniques to clean, analyze, and visualize the prompts. The goal is to gain insights into the structure, content, and vocabulary of the prompts.

## Project Overview

The project processes a collection of ChatGPT prompts using the following steps:

1. **Data Loading and Cleaning**:
   - Load the dataset of prompts.
   - Clean the text by converting it to lowercase, removing extra whitespace, special characters, HTML tags, contractions, punctuation, numbers, and stopwords.
   - Perform lemmatization to reduce words to their base form.

2. **Text Analysis and Feature Extraction**:
   - Extract keywords from the cleaned prompts using TF-IDF (Term Frequency-Inverse Document Frequency).
   - Visualize the distribution of word frequencies across all prompts.
   - Analyze prompt lengths and word counts using various plots.

3. **Visualizations**:
   - Generate visualizations to understand the structure and patterns in the dataset. These include:
     - **Distribution of Word Frequencies**: A line plot showing how frequently words appear in the dataset.
     - **Prompt Length vs. Word Count**: A scatter plot depicting the relationship between prompt length (characters) and word count.
   
## Key Features

### 1. Data Cleaning and Preprocessing
- **Lowercasing**: All text is converted to lowercase to ensure uniformity.
- **Whitespace Removal**: Extra spaces are removed to avoid inconsistencies.
- **Special Character Removal**: Non-alphanumeric characters are stripped from the text.
- **HTML Tag Removal**: Any HTML tags are removed from the text using BeautifulSoup.
- **Contraction Expansion**: Shortened forms like "isn't" are expanded to their full form.
- **Punctuation and Number Removal**: Punctuation marks and numbers are removed from the text.
- **Stopword Removal**: Common words like "the", "a", etc., are removed to focus on meaningful content.
- **Lemmatization**: Words are reduced to their base or root form (e.g., "running" → "run").

### 2. Text Analysis
- **TF-IDF Keyword Extraction**: Keywords from the prompts are extracted using TF-IDF to highlight important terms.
- **Word Frequency Distribution**: A line plot visualizing the distribution of word frequencies, showing how many words appear a certain number of times.
- **Prompt Length vs. Word Count**: A scatter plot visualizing the correlation between prompt length (in characters) and word count.

### 3. Visualizations
The project generates multiple plots:
- **Word Frequency Distribution**: A line graph that shows how many words occur with different frequencies.
- **Prompt Length vs. Word Count**: A scatter plot revealing the relationship between the length of prompts (in characters) and the number of words.

## Installation

To run this project locally, you will need to install the following dependencies:

pip install pandas nltk matplotlib seaborn tqdm wordcloud

## Usage

1. Clone the repository:
 
 git clone [https://github.com/zheenbekovtemirlan/zheenbekovtemirlan-nlp.git]

2. Navigate to the project directory:

cd zheenbekovtemirlan-nlp

3. Run the Jupyter notebook or script to execute the analysis and generate visualizations.

## Files

- chatprompts.csv`: The dataset containing the ChatGPT prompts.
- notebook.ipynb`: The Jupyter notebook containing the full analysis, including data cleaning, feature extraction, and visualization.
- README.md`: The documentation file explaining the project.

## Conclusion

This project provides an in-depth analysis of ChatGPT prompts, offering insights into the word usage, structure, and characteristics of the prompts in the dataset. 
The visualizations and analyses performed can help guide future improvements and understand the patterns within the prompts.

---
