# Cross-Cultural Analysis of Social Norms in Movies

## Project Overview
This research aims to explore the expression of social norms concerning pride and shame across Bollywood and Hollywood movies. By analyzing subtitles scraped from a broad range of films, this project investigates how different cultures interpret these self-conscious emotions and their associated social norms.

## Data Collection
### Subtitle Scraping
Implemented in Python using BeautifulSoup and Selenium for dynamic content interaction.
### Cleaning and Standardization
Removal of timestamps, null lines, and dialogues not contributing to context.
### Dialogue Combination
Dialogues split by ellipses were merged to maintain the integrity of conversational context.

## Methodology
### Data Processing
Details the steps taken to prepare the data for analysis.
### Analysis Techniques
#### Context Windows
For each mention of "pride" or "shame," adjacent dialogues were extracted to form a context window.
#### LDA Topic Modeling
Employed to categorize dialogues into thematic clusters.
#### Sentiment Analysis
Utilized Luke and Transformers to perform deeper linguistic and sentiment analysis.
#### Norm Extraction with LLMs
Large language models were prompted to identify and generate the social norms depicted in the dialogues.

## Results
The analysis highlighted distinct cultural differences, with specific examples from Bollywood and Hollywood.

## Visualizations
Graphical representations such as word clouds and bar graphs are shown.

