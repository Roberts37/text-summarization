# Text Summarization from Medium Articles

## Overview

The "Text Summarization from Medium Articles" project is a data science and natural language processing (NLP) exploration designed to extract valuable insights from Medium articles. The project encompasses web scraping, data manipulation, and text summarization techniques to generate concise summaries for a curated list of topics.

## Key Features

- **Medium Article Extraction:**
  - Utilizes web scraping techniques to search for articles on Medium across a curated list of topics.
  - Extracts essential information such as article titles, URLs, and other relevant metadata.

- **Data Management with Pandas:**
  - Implements a data pipeline using the Pandas library to organize and manage article data in a structured DataFrame.
  - Calculates and stores the length of each article's text for subsequent analysis.

- **Text Summarization Pipeline:**
  - Integrates the Hugging Face `transformers` library to create a summarization pipeline.
  - Develops a custom function for text summarization, generating concise summaries for each article.

- **Data Filtering and Export:**
  - Applies data filtering to include articles within a specific length range, ensuring relevance and coherence in the summaries.
  - Exports the refined dataset to a CSV file for further analysis or sharing.

## Technologies Used

- Python
- Pandas
- Beautiful Soup (for web scraping)
- Hugging Face Transformers (for pre-trained NLP models)
