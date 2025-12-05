# Sentiment_Finbert_embedding
This project develops an automated Natural Gas Market Intelligence pipeline that integrates document ingestion, summarization, and sentiment analysis using state-of-the-art language models trained for the financial domain.

The system processes both static EIA Natural Gas reports and dynamic web content from EIA Today in Energy, extracts relevant text, and applies advanced NLP methods to generate structured insights. Large Language Models (LLMs) are used to create human-interpretable summaries, while FinBERT, a domain-adapted variant of BERT trained on financial news articles, is used to compute sentiment scores and extract linguistic features at both the token and sentence level.

FinBERT originates from the BERT architecture by Google, which demonstrated exceptional performance across multiple NLP tasks through its bidirectional training and transformer-based encoding. FinBERT further specializes this capability by being pre-trained and optimized for financial language contexts, enabling more accurate recognition of tone, risk, and sentiment signals in industry-specific text.

The objective of this project is not to fine-tune or build an end-to-end model, but rather to harness FinBERT embeddings and sentiment outputs as reusable features for downstream analytical applications—including trend detection, text classification, risk scoring, clustering, extractive summarization, and time-series sentiment tracking of Natural Gas-related market communications.

# Features
Pre-processing pipeline including text cleaning, segmentation, and metadata structuring.

LLM-driven summarization to generate concise, decision-ready insights from long technical reports.

FinBERT-based sentence-level sentiment analysis tailored to financial language.

Token- and sentence-level embedding extraction for advanced analytics and model reuse.
