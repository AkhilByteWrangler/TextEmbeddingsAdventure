# TextEmbeddingsAdventure

# **Embarking on an Adventure Through the Embedding Space!**

Welcome to the whimsical journey of **Data the Doggo** and **Insight the Silly Cat** as they explore the enchanting realm of text embeddings! This repository is a delightful blend of playful storytelling and natural language processing techniques, aimed at visualizing and understanding the intricacies of embeddings.

## **Project Overview**

In the vast landscape of the **Embedding Space**, we utilize the powerful `all-MiniLM-L6-v2` model, celebrated on the **MTEB leaderboard** for its exceptional performance across various NLP tasks. Our exploration includes benchmarking this model against the **Banking77 Classification** task, providing a solid foundation for evaluating the effectiveness of our embedding visualizations.

### **Key Highlights:**

- **Data Source**: Dive into a treasure trove of **500,000 quotes**, spanning themes of love, philosophy, life, and the nature of existence. We've sampled a manageable dataset of **1000 quotes** to keep our exploration nimble while capturing a diverse array of ideas.

- **Dimensionality Reduction Techniques**:
  - **PCA (Principal Component Analysis)**: This method gives us a broad overview of the embedding landscape, capturing the main directions of variance. While PCA might not reveal distinct clusters, it lays the groundwork for understanding the overall structure.
  - **t-SNE (t-Distributed Stochastic Neighbor Embedding)**: Known for its ability to uncover local patterns, t-SNE reveals groups of similar thoughts, helping us visualize the relationships between quotes in a more detailed manner. Although it can be temperamental, it’s excellent for discovering hidden friendships among quotes.
  - **UMAP (Uniform Manifold Approximation and Projection)**: UMAP strikes a balance between local and global structures, providing a cohesive view of the embedding space. It reveals meaningful clusters while maintaining the integrity of broader relationships.

- **Interactive Visualizations**: Using libraries such as **Matplotlib** and **Seaborn**, we create stunning plots that showcase the results of our dimensionality reduction techniques. Each plot serves as a map of the ideas contained within our quotes, allowing viewers to see connections and patterns.

## **Learning Objectives**:

- **Understanding Embeddings**: Gain insights into how text is transformed into numerical representations, capturing semantic meaning.
- **Visualization Techniques**: Explore the strengths and weaknesses of PCA, t-SNE, and UMAP in revealing different aspects of embedding spaces.
- **Critical Thinking**: Reflect on how visualizations can inform our understanding of data and highlight the importance of choosing the right method for different analytical tasks.

## **Why This Matters**:
Exploring embeddings and visualizing them is crucial for various applications in NLP, such as sentiment analysis, recommendation systems, and semantic search. By delving into this project, we aim to not only understand how different embeddings work but also provide a fun and engaging narrative that makes the complexities of NLP accessible.

Join Data and Insight on their adventure and uncover the wisdom waiting in the Embedding Space!

## **How to Run?**:
[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AIPI-590-XAI/Duke-AI-XAI/blob/dev/templates/template.ipynb)
