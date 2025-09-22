# bigquery-ai
---
<img width="3596" height="2008" alt="Cover" src="https://github.com/user-attachments/assets/c8fc852f-e470-44b8-83f4-7a2010bcc081" />

This repository contains code for our work in [Kaggle's BigQuery AI Competition](https://www.kaggle.com/competitions/bigquery-ai-hackathon/writeups). We adopted **Approach 2: The Semantic Detective** by leveraging BigQuery's (BQ) native vector search capabilities to go beyond simple keyword matching and vector search. We utilized BQ's `VECTOR_SEARCH()` and `ML.GENERATE_EMBEDDING()` functions with Gemini to transform product descriptions into meaningful vectors. Then we implemented a novel vector search strategy that understands user interactions over time, rather than just relying on simple text semantics.
