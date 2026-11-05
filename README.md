# NLP Text Summarization with SpaCy and NLTK 

##  Description
An extractive text summarization pipeline built to automatically generate concise summaries of long documents. This project demonstrates core Natural Language Processing (NLP) techniques to identify and extract the most significant sentences from a given text based on word frequency scoring. The implementation focuses on the historical context and engineering achievements of the Space Shuttle Discovery.

##  Technologies
- **Language:** Python
- **NLP Libraries:** SpaCy (`en_core_web_sm`), NLTK (Tokenizers, Stopwords)
- **Data Structures:** Python Dictionaries, `heapq` (`nlargest`)
- **Environment:** Google Colab

## ⚙️ Functionality
- **Text Preprocessing:** Tokenizes text into words and sentences using NLTK. Removes common English stop words and punctuation to focus on meaningful content.
- **Word Frequency Analysis:** Calculates the normalized frequency of each word in the document using SpaCy to determine the most important keywords.
- **Sentence Scoring:** Evaluates and scores every sentence based on the cumulative frequency of the significant words it contains.
- **Extractive Summarization:** Automatically extracts the top-scoring sentences (dynamically selecting 30% of the total sentences, with a minimum of 3) to form a coherent and informative summary of the original text.
