# Contributors
- [Selsabeel A.](https://github.com/SelsabeelA/)
- [Abdelrahman Mohamed](https://github.com/AbdoAlshoki2/)

# Word2VecModel
A text similarity analysis project using Word2Vec embeddings and multiple similarity measures (Cosine, Jaccard, Euclidean) to compare document contents and visualize their relationships.

Long Description (for README):
This project demonstrates text similarity analysis using Word2Vec embeddings for document representation. It processes a set of documents, tokenizes and lemmatizes the text, and generates word embeddings using a Word2Vec model trained on the Reuters dataset. The embeddings are then used to compute various similarity measures between documents, including:

Cosine Similarity: Measures the cosine of the angle between document vectors.
Jaccard Similarity: Computes the similarity based on shared words between documents.
Euclidean Distance: Quantifies the straight-line distance between document vectors in the embedding space.
The results are presented as similarity matrices, and a heatmap is generated to visually represent the relationships between the documents. Furthermore, Multidimensional Scaling (MDS) is used to project the document similarities onto a 2D space for visualization, allowing for an intuitive understanding of the closeness between different documents.

Features:
Word2Vec-based embeddings to represent document semantics.
Multiple similarity measures (Cosine, Jaccard, Euclidean) to evaluate document closeness.
Heatmap visualization of document distances.
MDS-based 2D visualization for document similarity analysis.
