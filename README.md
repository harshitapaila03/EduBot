# EduBot: Your Knowledgeable Companion for Science and History

## Introduction

EduBot is an innovative educational assistant designed to answer queries about historical events and scientific concepts. By leveraging cutting-edge natural language processing (NLP) techniques, EduBot provides accurate, concise, and contextually relevant responses to help students, researchers, educators, and knowledge seekers.

EduBot integrates both structured and unstructured data sources to provide comprehensive answers, showcasing the potential of NLP in educational applications.

EduBot employs a robust framework to analyze user queries and categorize them based on historical and scientific contexts. The analysis ensures that responses are relevant and informative, tailored to the user's needs.

### Key Features:

1. **Preprocessing and Transformation:**
   - Tokenizes and removes stop-words using spaCy.
   - Performs Named Entity Recognition (NER) to identify key entities in queries.

2. **Data Retrieval:**
   - Fetches semantic data via SPARQL queries from WikiData.
   - Accesses unstructured content from Wikipedia API.

3. **Summarization:**
   - Utilizes a pre-trained BART model to generate concise summaries from long text.

4. **Scoring System:**
   - Assigns relevance scores for historical and scientific contexts of queries to ensure accurate and targeted responses.

5. **Visualization and Interaction:**
   - Provides a Streamlit-based interface for real-time query processing and response generation.

---

## Dataset

EduBot uses datasets comprising both structured and unstructured data for analysis:

- **WikiData**: For semantic, structured content.
- **Wikipedia**: For detailed, unstructured content.



---

## Example Queries and Results

### Example 1: "What is the speed of the light?"
 

 <img width="440" alt="image" src="https://github.com/user-attachments/assets/feefd73c-236f-467a-aca9-000480f9d8ea">




<img width="394" alt="image" src="https://github.com/user-attachments/assets/963814b8-0c0c-499c-98d7-41ed00c4728a">

 





### Example 2: "Who was Napoleon Bonaparte?"




<img width="210" alt="image" src="https://github.com/user-attachments/assets/823b0059-df1e-4c0f-a89a-7a9d1da786fc">





