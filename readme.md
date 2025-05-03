# PyCleanText

[![PyPI version](https://img.shields.io/pypi/v/PyCleanText.svg)](https://pypi.org/project/PyCleanText/)
[![PyPI downloads](https://img.shields.io/pypi/dm/PyCleanText.svg)](https://pypi.org/project/PyCleanText/)
[![Python version](https://img.shields.io/pypi/pyversions/PyCleanText.svg)](https://pypi.org/project/PyCleanText/)

**PyCleanText** is a simple Python package designed to clean and preprocess text data. It removes unwanted noise from raw text by handling tasks like:

- Lowercasing text
- Removing URLs, punctuation, numbers, and special characters
- Removing stopwords (common words like "the", "a", "and", etc.)
- Stripping HTML tags
- Removing duplicate consecutive words
- Generating a cleaned text file

## Features

- **Comprehensive cleaning**: Removes unwanted elements like URLs, special characters, and stopwords.
- **Normalization**: Converts text to lowercase and standardizes it for analysis.
- **Duplicate word removal**: Cleans up consecutive duplicate words for better clarity.
- **File input and output**: Load raw text from a file and save the cleaned text to a new file.

## Installation

You can install **PyCleanText** directly from the Python Package Index (PyPI):

```bash
pip install PyCleanText
```
## Usage
```bash
from PyCleanText import PyCleanText

file_path = 'input.txt'  
output_file_path = 'cleaned_output.txt' 

PyCleanText(file_path, output_file_path)
```
### OR

```bash
PyCleanText(file_path)
```
