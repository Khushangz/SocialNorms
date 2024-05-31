Cross-Cultural Analysis of Social Norms in Movies

Project Overview

This research aims to explore the expression of social norms concerning pride and shame across Bollywood and Hollywood movies. By analyzing subtitles scraped from a broad range of films, this project investigates how different cultures interpret these self-conscious emotions and their associated social norms.

Data Collection

The dataset comprises over 5,000 movies from both Bollywood and Hollywood, extracted and cleaned to focus on dialogues involving the themes of pride and shame. Specific challenges overcome during data collection included handling diverse encoding formats and extensive manual filtering to ensure data reliability.

Methodology

Data Processing
Subtitle Scraping: Implemented in Python using BeautifulSoup and Selenium for dynamic content interaction.
Cleaning and Standardization: Removal of timestamps, null lines, and dialogues not contributing to context.
Dialogue Combination: Dialogues split by ellipses were merged to maintain the integrity of conversational context.
Analysis
Context Windows: For each mention of "pride" or "shame," adjacent dialogues were extracted to form a context window, which aids in understanding the scenario around the mentioned emotion.
LDA Topic Modeling: Employed to categorize dialogues into thematic clusters that represent underlying social norms.
Sentiment Analysis: Utilized Luke and Transformers to perform deeper linguistic and sentiment analysis.
Norm Extraction with LLMs: Large language models were prompted to identify and generate the social norms depicted in the dialogues.
Results

The analysis highlighted distinct cultural differences:

Bollywood: Emphasizes community and familial honor, with shame often linked to deviance from traditional roles.
Hollywood: Focuses on individualism, with pride frequently connected to personal success and ethical actions.
Visualizations

Graphical representations such as word clouds and bar graphs illustrate the frequency and distribution of themes across the datasets.
