# word_embeddings
This is an example of how you can train your own word embeddings and track that progress via logging the similarity change over time and visualizing the results in 3D. <br>
We use Word2Vec here as the example model but you can replace it with any embedding model once the output is an embedding that you can use for things like cosine similarity and then visualize them via dimsionality reduction with techniques as PCA <br>

## 1. Generate your dataset
First you will need to generate your own dataset via the `custom_language_dataset.ipynb` notebook. <br>
You can tune this dataset to whatever you like to see different results. So it is worth experimenting with. <br>
As a start we will use a simply random dataset and one where the relationship between terms in our dataset are easily identified. <br>

## 2. Train your embeddings
Next you can use the example Word2Vec model to train some word embeddings via the `train_track_embeddings.ipynb` notebook.

## 3. Track your results via Neptune
And finally we will look at how the similarity changes over time for an example term and visualize the 3D interactive plot of the embeddings as well. <br>
This should give us some insight into what information is being encooded into these embeddings <br>

`
