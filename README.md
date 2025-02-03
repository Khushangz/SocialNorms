# **Cross-Cultural Analysis of Social Norms in Bollywood and Hollywood Movies**

## **Project Description**  
This project investigates **cross-cultural variations in social norms** by analyzing the self-conscious emotions of **shame and pride** in **Bollywood and Hollywood** movies. By leveraging **5,435 movie subtitles**, we extracted **10,000+ social norms**, offering insights into how these emotions manifest across different cultures.

## **Repository Contents**  
- `Code.ipynb` – Python notebook for **scraping and processing** Bollywood and Hollywood subtitles.  
- `Input/` – Processed dataset containing **movie dialogues** with emotion-based context windows.  
  - **Example (Input File)**:  
    ```
    Movie_id: WP0_holly | Movie_name: Big Hero 6 | Message: Aunt Cass? - FRED: Unless it's moldy. We'll, uh... We'll catch up, okay? Sure, I'm so proud of you. Both of you. BOTH: Thanks, Aunt Cass.
    ```  
- `Output/` – Extracted structured data on **who experiences emotions** and **why**.  
  - **Example (Output File)**:  
    ```
    Message_id: s2_bolly | Shame_who: speaker | Gender: female | Cause: expressing love for a man
    ```  
- `Results/` – Statistical analysis, visualizations, and insights into **cultural differences** in self-conscious emotions.  

## **Methodology**  
### **1. Data Collection**  
- **Automated web scraping** of **Bollywood and Hollywood** movies (post-1990) using **Python (BeautifulSoup, Requests, OS)**.  
- Extraction of **subtitles** to capture dialogues containing the words **shame** and **pride**.  

### **2. Data Processing**  
- **Text cleaning** to remove noise and align with NLP processing standards.  
- Context window extraction around **emotion-related** terms.  

### **3. Analysis**  
- **NLP techniques** applied:  
  - **Latent Dirichlet Allocation (LDA)** for topic modeling.  
  - **Linguistic Inquiry and Word Count (LIWC)** for psycho-social categorization.  
  - **Prompt engineering** to extract structured insights.  
- **Statistical comparison** of Bollywood vs. Hollywood **cultural expressions** of shame and pride.  

## **Results & Findings**  
The analysis demonstrates **cultural distinctions** in self-conscious emotions:  
- **Bollywood** emphasizes **familial honor and societal roles**.  
- **Hollywood** focuses on **individual achievements and ethical behavior**.  
- **Visualization and detailed results** are in the `Results/` directory.  

## **License**  
This dataset and code are released under the **Apache License 2.0**. See the [`LICENSE`](LICENSE) file for details.
