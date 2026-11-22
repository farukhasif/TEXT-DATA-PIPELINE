# TEXT-DATA-PIPELINE

A Python-based NLP text data pipeline for collecting, cleaning, preprocessing, and validating real-world text datasets.

## Project Objectives

- Set up a Python environment.
- Verify libraries and GPU availability.
- Collect 5,000+ real-world text documents.
- Clean and preprocess text data.
- Remove HTML tags and unnecessary whitespace.
- Perform Unicode normalization and language filtering.
- Write unit tests for preprocessing functions.
- Save the cleaned dataset in Parquet or JSONL format.

## Technologies

- Python
- Pandas
- spaCy
- Sentence Transformers
- ChromaDB
- pytest

## Project Structure

- `data/raw/` – Raw datasets
- `data/processed/` – Cleaned datasets
- `src/preprocessing.py` – Text preprocessing functions
- `tests/test_preprocessing.py` – Unit tests
- `scripts/verify_env.py` – Environment verification

## Project Status

Week 1: Environment, Data Ingestion & Preprocessing.

## Goal

To build a clean, modular, and reliable text preprocessing pipeline for NLP and machine learning applications.
