# Implementing Retrieval Augmented Generation from Scratch on Google Colab

## Overview
This notebook is designed to process data from a PDF file and do Retrieval Augmented Generation (RAG) while considering resource limitations on Google Colab. It offers flexibility in adjusting to different devices and resource constraints.

## Setup Instructions and General Information
### HuggingFace Drive Integration
You will need a HuggingFace account and to create an access token.

### Google Drive Integration
If you want to utilise the code that uses Google Drive, you have set up appropriate folder manually on Google Drive and put the PDF file you want to process in there.



## Tested Models
The notebook has been tested on a Google Colab machine with 16GB VRAM. Here are the models that have been tested:
- **gemma-2b-it**: Suitable when `SMALL_VRAM=False`.
- **gemma-7b-it**: Works on CUDA (`'cuda'`) with `SMALL_VRAM=True`.

## Credits
Credits to Daniel Bourke, whose video [link here](https://www.youtube.com/watch?v=qN_2fnOPY-M) served as the basis for this project.
