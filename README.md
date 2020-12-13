# word_embeddings
This is an example of how you can train your own word embeddings and track that progress via logging the similarity change over time and visualizing the results in 3D.
We use Word2Vec here as the example model but you can replace it with any embedding model once the output is an embedding that you can use for things like cosine similarity and then visualize them via dimsionality reduction with techniques as PCA

## Generate your dataset
First you will need to generate your own dataset via the `custom_language_dataset.ipynb` notebook.

`
