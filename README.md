# **Social Norms in Cinema: A Cross-Cultural Analysis of Shame, Pride and Prejudice**

## **Project Description**  
Shame and pride are social emotions expressed across cultures to motivate and regulate people's thoughts, feelings, and behaviors. In this paper, we introduce the first cross-cultural dataset of over shame/pride-related expressions, with underlying social expectations from **5.4K** Bollywood and Hollywood movies. We examine how and why {shame and pride} are expressed across cultures using a blend of psychology-informed language analysis combined with large language models.

## **Repository Contents**  
- `Input_Files/` – Processed dataset containing **movie dialogues** with emotion-based context windows.  
  - **Example (Input File)**:  
    ```
    Movie_id: WP0_holly | Movie_name: Big Hero 6 | Message: Aunt Cass? - FRED: Unless it's moldy. We'll, uh... We'll catch up, okay? Sure, I'm so proud of you. Both of you. BOTH: Thanks, Aunt Cass.
    ```  
- `Output_Files/` – Extracted structured data on **who experiences emotions** and **why**.  
  - **Example (Output File)**:  
    ```
    Message_id: s2_bolly | Person Who Felt The Emotion: speaker | Gender: female | Cause: expressing love for a man
    ```  
- `Results/` – Statistical analysis, visualizations, and insights into **cultural differences** in self-conscious emotions.  

## **Methodology**  
### **1. Data Collection**  
- **Automated web scraping** of **Bollywood movies (post-1990) using **Python (BeautifulSoup, Requests, OS)**.  
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
  
### **BibTeX Citation**
```bibtex
@inproceedings{SocialNorms2025,
  title     = {Social Norms in Cinema: A Cross-Cultural Analysis of Shame, Pride and Prejudice},
  author    = {Sunny Rai and Khushang Zaveri and Shreya Havaldar and Soumna Nema and Lyle Ungar and Sharath Chandra Guntuku},
  booktitle = {The 2025 Annual Conference of the Nations of the Americas Chapter of the ACL},
  year      = {2025},
  url       = {https://openreview.net/forum?id=NLX2ynQhOZ}
}
```

## **License**  
This dataset and code are released under the **Apache License 2.0**. See the [`LICENSE`](LICENSE) file for details.
