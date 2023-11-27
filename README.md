# Pitch Deck Excellence: Identifying the Winning Startup (NLP based)

**"Empowering startups with AI-driven insights for pitch deck optimization."**

## About the Project
Our project provides an AI model for evaluating startup pitch decks, focusing on the key factors that contribute to investment and market success.

## Evaluation Criteria
Our AI model assesses pitch decks based on comprehensive criteria, each carrying a specific weightage contributing to the total score:

- Identification of the Problem: 15%
- Sizing of the Problem: 10%
- Clarity on Product Idea/Identity: 10%
- Understanding of Competitors and Landscape: 10%
- Go-to-Market (GTM) Strategy: 10%
- Business Model: 10%
- Team Strength and Dynamics: 20%
- Product Differentiator: 15%

## Methodology
- **Data Collection**: Utilized a curated set of startup pitch decks provided in an Excel sheet with links, ensuring data privacy.
- **Text Extraction & Preprocessing**:  Employed advanced text extraction techniques from .pdf and .pptx formats, followed by NLTK-based preprocessing for analysis readiness.
- **Model Training & Optimization**: Leveraged machine learning models like Random Forest and Gradient Boosting, optimized through GridSearchCV, and enhanced with ensemble methods.

## Text Preprocessing
Our AI model employs a robust text preprocessing pipeline to analyze the content of startup pitch decks effectively. Here's an overview of the process:

- **Extraction**: We extract textual content from various document formats, including PDFs and PPTs, using specialized libraries.
- **Cleaning**: The extracted text undergoes a cleaning process to standardize it, ensuring consistency across different sources.
- **Tokenization**: We break down the text into individual words or tokens, facilitating a detailed analysis of the content.
- **Lemmatization**: This step involves converting words to their base or dictionary form, helping in the accurate assessment of word usage and context.
- **Stopword Removal**: Common words that offer little value in understanding the pitch decks' content, like 'the', 'is', and 'and', are removed.
- **Vectorization (TF-IDF)**: Finally, we convert the preprocpreprocessed text into a numerical format using Term Frequency-Inverse Document Frequency (TF-IDF) vectorization. This technique helps in highlighting the most important words for further analysis by our machine learning models.

Through this preprocessing pipeline, our AI system can effectively interpret and analyze the content of each pitch deck, laying the groundwork for accurate scoring and evaluation.

## Dataset Confidentiality
The dataset used for this project, comprising various startup pitch decks, is not included in this repository due to confidentiality agreements and privacy concerns.

## Results & Insights
- **Model Accuracy**: Achieved an overall accuracy of 61.7% in pitch deck evaluation.
  
![image](https://github.com/preetham-reddy-bathula/SmartPitchDeckEvaluation-using-MachineLearning/assets/65440305/df199924-c9ba-4378-ba92-29e336c8fb3f)

## Conclusion
Our AI-driven system marks a significant stride towards supporting technology in enhancing the startup ecosystem, offering valuable insights to refine pitch presentations for better investment opportunities.

---


Connect with me on LinkedIn: 

[![LinkedIn](https://img.icons8.com/color/48/000000/linkedin.png)](https://www.linkedin.com/in/preetham-kumar-reddy-b-b6821116b/)


