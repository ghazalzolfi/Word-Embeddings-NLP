
# Word Embeddings: Exploration, Visualization, and Applications

This repository provides a comprehensive exploration into word embeddings—dense numerical representations of words capturing semantic meaning. It involves using pre-trained embeddings (GloVe), training custom embeddings from scratch via co-occurrence matrices and Singular Value Decomposition (SVD), and applying these embeddings practically in sentiment analysis tasks.

### Project Overview:

### **1. Exploring Pre-trained Embeddings (GloVe):**
- **Objective**: Understand and visualize semantic relationships between words using GloVe embeddings.
- **Methodology**:
  - Loaded pre-trained GloVe embeddings trained on extensive Wikipedia and Gigaword corpora.
  - Analyzed and visualized semantic analogies and relationships (e.g., man-woman relationships).

### **2. Embedding Visualization:**
- **Objective**: Provide intuitive visual representations of high-dimensional embeddings.
- **Methods**:
  - Used dimensionality reduction techniques like PCA and t-SNE to visualize embeddings in 2-D space clearly illustrating semantic clustering.

### **3. Evaluating Embeddings:**
- **Cosine Similarity**: Measured semantic similarity between word vectors to quantify embedding quality.
- Conducted small-scale semantic tests to illustrate embeddings' ability to capture linguistic nuances.

### **4. Training Custom Word Embeddings:**
- **Objective**: Understand and implement methods to generate embeddings from raw text data.
- **Implementation Steps**:
  - Preprocessed textual datasets through tokenization and phrase detection.
  - Constructed word co-occurrence matrices reflecting semantic contexts.
  - Applied SVD on co-occurrence matrices to obtain effective low-dimensional embeddings.

### **5. Sentiment Analysis on Movie Reviews:**
- **Objective**: Demonstrate practical application of word embeddings in machine learning tasks.
- **Methodology**:
  - Built and trained sentiment analysis models leveraging custom-trained word embeddings.
  - Evaluated models on MDB movie review datasets, demonstrating embeddings' effectiveness in capturing sentiment.

### Key Learning Outcomes:
- Deep understanding of word embeddings, including popular techniques like GloVe and co-occurrence-based methods.
- Practical skills in embedding visualization and semantic evaluation.
- Experience in training and fine-tuning custom embeddings tailored to specific NLP tasks.
- Insights into the application of word embeddings in real-world tasks like sentiment analysis.

### Libraries and Tools Used:
- Python
- NumPy, Pandas (Data handling and numerical computations)
- Gensim (Embedding management and analysis)
- scikit-learn (Evaluation and dimensionality reduction)
- Matplotlib (Visualization)

This project establishes foundational and practical understanding of word embeddings essential for advanced natural language processing tasks and applications.
