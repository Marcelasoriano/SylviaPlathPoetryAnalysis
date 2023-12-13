# Sylvia Plath Poems Analysis Notebook

## Notebook Description
This Jupyter notebook is designed for a comprehensive literary analysis of Sylvia Plath's poems, using a variety of Python libraries for data manipulation, natural language processing (NLP), and visualization. The notebook is structured into distinct sections, each focusing on different aspects of text analysis and visualization.

## Sections of the Notebook
- **Sentiment Analysis Over Time**: Analyzes the sentiment of poems across different years, including 'Juvenilia'. Uses TextBlob for sentiment polarity calculation and Plotly for visualization.
- **Sentiment Variability (Standard Deviation)**: Calculates the standard deviation of sentiments for each year, providing insight into the emotional variability within the poems.
- **Keyword and Phrase Analysis**: Extracts and visualizes the most common words and bigrams in the poems using NLTK and Plotly.
- **Named Entity Recognition (NER)**: Identifies and categorizes named entities in the poems using spaCy, visualized as a bar chart.
- **Data Loading and Preprocessing**: Involves loading data from CSV and DOCX files and preprocessing steps like tokenization and lemmatization.

## How to Use the Notebook
### Setup
- Ensure all necessary libraries are installed: `pandas`, `plotly.graph_objects`, `datetime`, `nltk`, `spacy`, `string`, `collections`, `docx`, `plotly.express`, `textblob`.
- Download `PlathPoems.csv`, `PlathPoems.docx`, and `poems_by_year.csv`. Load them into the "files" section of this notebook.

### Running Sections
- Execute each cell sequentially. Each section includes code for analysis and visualization.
- Modify parameters like file paths or visualization settings as needed.

### Interpreting Results
- View and interpret the visualizations generated by the notebook for insights into sentiment trends, word usage, and named entity occurrences in the poems.

#### By: Marcela Soriano
