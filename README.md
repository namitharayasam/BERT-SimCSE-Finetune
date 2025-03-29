# 🚀 Contrastive Learning for Enhanced Sentence Representations using SimCSE (BERT-based)

This project fine-tunes SimCSE (Simple Contrastive Learning of Sentence Embeddings) using the SNLI (Stanford Natural Language Inference) dataset to generate robust sentence embeddings. The embeddings are then used for semantic similarity and clustering tasks**.

---

## 📝 **Introduction**
SimCSE is a contrastive learning method that fine-tunes BERT models to learn better sentence embeddings by pulling similar sentences closer and pushing dissimilar ones apart in the embedding space.

- **Supervised SimCSE:** Uses **SNLI dataset** (premise & hypothesis pairs).
- **Unsupervised SimCSE:** Uses **dropout noise** for self-supervision.

This project fine-tunes a SimCSE model using the supervised approach.
