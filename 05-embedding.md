# What is embedding?

Embedding a is a numerical representations of data. They are primarily used to to represent _unstructured_ data such as images, videos, audios, text etc.
The representation capture the semantic meaning of what is being embedded.

We can use the embedding to compare the similarity between two pieces of information.

## Generating Embeddings

For text, we can use SentenceTransformers or [fastembed](https://qdrant.github.io/fastembed/) and even LLM like OpenAI or Google's Palm to generate embedding.

For image, we can use CLIP.

## How to compare embeddings?

We can use cosine similarity to compare the similarity between two embeddings.



## How to evaluate embeddings?

Use MTEB leaderboard.
