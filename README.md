# Automated Cover Letter Generation System

## Overview
This project provides an automated system for generating professional cover letters based on a given resume and job description. It leverages state-of-the-art natural language processing models from Hugging Face and implements efficient model quantization for optimized performance.

## Features
- Text Extraction: Extract text from PDF and TXT files.
- Cover Letter Generation: Generate tailored cover letters using a pre-trained language model.
- Efficient Model Loading: Utilize 4-bit quantization for improved performance on available hardware.

## Requirements
- Python 3.x
- Libraries:
  - transformers
  - torch
  - fitz (PyMuPDF)
  - json

## Installation
1. Clone the repository: ```git clone https://github.com/your-repo/cover-letter-generator.git
cd cover-letter-generator```
2. Install the required libraries: ```pip install transformers torch pymupdf json```
3. Place your Hugging Face API token in a config.json file: ```{"HF_TOKEN":"your_huggingface_api_token"}```

## License
This project is licensed under the MIT License. See the LICENSE file for details.

