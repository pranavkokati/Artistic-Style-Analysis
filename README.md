# Artistic-Style-Analysis

In this notebook, we’ll explore how to use multimodal embeddings and computed attributes to analyze artistic styles in images. We’ll use the WikiArt dataset from 🤗 Hub, which we will load into FiftyOne for data analysis and visualization. We’ll dive into the data in a variety of ways:

Image Similarity Search and Semantic Search: We’ll generate multimodal embeddings for the images in the dataset using a pre-trained CLIP model from 🤗 Transformers and index the data to allow for unstructured searches.

Clustering and Visualization: We’ll cluster the images based on their artistic style using the embeddings and visualize the results using UMAP dimensionality reduction.

Uniqueness Analysis: We’ll use our embeddings to assign a uniqueness score to each image based on how similar it is to other images in the dataset.

Image Quality Analysis: We’ll compute image quality metrics like brightness, contrast, and saturation for each image and see how these metrics correlate with the artistic style of the images.

Credit to Jacob Marks for his course on HuggingFace
Check it his course out here: https://huggingface.co/learn/cookbook/analyzing_art_with_hf_and_fiftyone
