# Runway Retrieval Dataset
This directory contains a domain-specific text retrieval dataset for runway maintenance and airfield operations. It can be used for semantic retrieval, ranking, and query-text matching experiments.

## Files
- runway-queries.json: query set organized by anonymized IDs
- runway-document.json: text/document set organized by anonymized IDs
- train.csv, dev.csv, test.csv: triples of queries, related texts, and relevance labels for training, validation, and testing
- runway_retrieval.py: example script for retrieval training and evaluation

## Dataset Scale
- 766 queries
- 1352 text/document entries
- 10105 test triples


