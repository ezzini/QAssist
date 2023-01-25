# INSTALL

QAssist artifact is composed of two main notebooks. 
The artifact can be executed in a local environment or in the cloud (e.g., Google Colab).


## Local environment

Clone and install the required libraries

#### From Github
```bash
git clone https://github.com/ezzini/QAssist.git
cd QAssist
pip install -r requirements.txt 
```
#### From FigShare
Download and extract the content
navigate to the downloaded directory
```bash
cd path/to/dir
pip install -r requirements.txt 
```

## Cloud environment
[![Open Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

Run the first cell in each notebook to install the necessary libraries
The first cell of *IR_notebook.ipynb* notebook is:
```python
!pip install beir rank_bm25 tensorflow-text wikipedia python-docx
```
The first cell of *MRC_notebook.ipynb* notebook is:
```python
!pip install --upgrade pip
!pip install git+https://github.com/deepset-ai/haystack.git#egg=farm-haystack[colab]
!python -m spacy download en 
!python -m spacy download en_core_web_lg
```
Each cell will install the required libraries and their dependencies

## Contributing
Pull requests are welcome. For major changes, open an issue to discuss what you would like to change.
