# Implementing Retrieval Augmented Generation from Scratch on Google Colab

## Overview
This notebook is designed to process data from a PDF file into embeddings, store them, do similarity search using them and do Retrieval Augmented Generation (RAG) based on parts of the PDF that are simillar to the prompt, all while considering resource limitations on Google Colab.

## Setup Instructions and General Information
### HuggingFace Integration
You will need a HuggingFace account and to create an access token.

### Google Drive Integration
If you want to utilise the code that uses Google Drive, you have set up appropriate folder manually on Google Drive and put the PDF file you want to process in there.

### Regarding the PDF
`human-nutrition-text.pdf` is used in the notebook and is provided. You can use it as well, but you should also be able to use any other PDF. You will probably need to modify the `FIRST_PAGE_NUMBER` variable. There is also a little bit of code written specific to process data from `human-nutrition-text.pdf`. Those parts are denoted in the comments of the notebook.

### Regarding using different LLMs
So far I mainly tested this with `gemma` models. To use different models you might need to change the code a little bit. Namely the part that formats the input that is passed to the model. Said part is denoted in the code via comments.

## Tested Models
The notebook has been tested on a Google Colab machine with 16GB VRAM. Here are the models that have been tested:
- **gemma-2b-it**: Use `SMALL_VRAM=False`.
- **gemma-7b-it**: Works on `'cuda'` with `SMALL_VRAM=True`.

## Feedback
This code is written mainly for learning purposes so any feedback and comments are VERY much appreciated. Please check my bio for all up to date socials.

## Credits
Credits to Daniel Bourke, whose video [link here](https://www.youtube.com/watch?v=qN_2fnOPY-M) served as the basis for this project.
