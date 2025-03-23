# 🎬 Movie Subtitle Search Engine with Semantic Search

This project builds a semantic search engine for movie subtitles, allowing users to find movies and dialogues based on a given text query or audio clip.

## Features
- **Subtitle Processing:** Extracts and cleans text from a subtitle database.
- **Data Chunking:** Splits subtitles into meaningful semantic chunks.
- **Text Embeddings:** Uses Sentence Transformers to convert text into vector representations.
- **Vector Database (ChromaDB):** Stores embeddings for fast similarity search.
- **Semantic Search:** Finds relevant subtitles using Cosine Similarity.

## Tech Stack
- Python, Pandas, Regex → Text Processing
- Sentence Transformers → Embeddings
- ChromaDB → Vector Storage
- SQLite → Subtitle Database
