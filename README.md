# Hindi Poetry RAG: Ecological and Cultural Elements

## Project Overview

This project explores the use of Retrieval-Augmented Generation (RAG) to retrieve and interpret ecological and cultural references in Hindi poetry, using selected passages from *Kamayani* by Jaishankar Prasad.

The project combines multilingual text embeddings, semantic retrieval, and a generative language model to answer questions grounded in retrieved poetic passages.

## Research Focus

- Flora and fauna in Hindi poetry
- Rivers, water and landscapes
- Natural elements and seasons
- Cultural and metaphorical meanings
- Human–nature relationships

## Primary Text

*Kamayani* — Jaishankar Prasad

The experimental corpus includes selected passages from three sargs:

- Chinta (चिंता)
- Asha (आशा)
- Shraddha (श्रद्धा)

## Methodology

1. Prepared a small poetry corpus containing 15 passages.
2. Divided the passages into 43 text chunks.
3. Generated multilingual embeddings using `paraphrase-multilingual-MiniLM-L12-v2`.
4. Implemented semantic retrieval using cosine similarity.
5. Retrieved relevant passages for user queries.
6. Generated context-grounded Hindi answers using Gemini.
7. Conducted preliminary manual relevance assessment of retrieved passages.
8. Created flora-fauna frequency analysis and a co-occurrence network using Gephi.

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Sentence Transformers
- Gemini API
- Gephi
- GitHub

## Preliminary Outputs

- 15 poetry passages
- 43 text chunks
- 384-dimensional text embeddings
- Semantic retrieval results
- Preliminary manual retrieval evaluation
- Flora and fauna frequency visualization
- Co-occurrence network with 10 nodes and 19 edges

## Research Ethics and Limitations

The project is an experimental prototype, not a complete analysis of the entire *Kamayani* text.

The corpus covers only three sargs and the keyword-based ecological analysis may miss synonyms, metaphorical references and inflected word forms.

Generated interpretations may not capture every literary nuance. Therefore, retrieved passages are treated as supporting evidence rather than definitive interpretations.

The source text is attributed to its respective source. API credentials are not included in the repository.
