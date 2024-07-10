# Implementing Retrieval Augmented Generation from scratch on Google Colab
This notebook was designed with limitations of resources from Google Colab in mind, so it is meant to be quite adjustable when it comes to devices and resources
This notebook is also designed to store files (the pdf to do RAG from and embeddings) in the google drive. You might need to create apropriate folders manually

Tested models on 16GB VRAM Google Colab machine:
gemma-2b-it (can do SMALL_VRAM=False)
gemma-7b-it (works on 'cuda' with SMALL_VRAM=True)

Credits to Daniel Bourke, as the base of this project was written following his video: https://www.youtube.com/watch?v=qN_2fnOPY-M
