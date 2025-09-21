# NLP Text Similarity & Auto Tagging

A system for detecting semantic similarity between texts and performing **automatic tagging** using Natural Language Processing (NLP) techniques.  

The project leverages **Word2Vec embeddings** and **KNN classification** to identify related questions, compute text similarity, and assign relevant tags.

---

##  Features
- **Text Preprocessing**
  - Lowercasing
  - Removing HTML/XML tags
  - Removing punctuation
  - Removing stopwords
  - Word stemming (PorterStemmer)
- **Word Embedding**
  - Trained Word2Vec model with vector size `200` and window size `10`
- **Similarity Measurement**
  - Cosine similarity for sentence and word comparisons
- **Automatic Tagging**
  - Assigns relevant labels based on semantic similarity
- **Evaluation**
  - Classification with KNN  
  - Achieved ~**86% accuracy** on validation data
