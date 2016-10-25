# NLP Workshops
Introduction and tutorial about Natural Language Processing.
This is meant to be presented at the [Data For Good](http://www.dataforgood.fr/) NLP workshops, it will be extended over time.

##Requirements

**Python 2.7**

http://docs.python-guide.org/en/latest/starting/installation/

**pip (Package Manager for python)**

https://pip.pypa.io/en/stable/installing/

**Python modules**

```bash
pip install nltk word2vec unidecode
```

**Jupyter Notebook**

```bash
pip install jupyter
```

**NLTK models**

```bash
python -c 'import nltk; nltk.download()'
```

In the Models tab of the downloader interface, install Average Perceptron Tagger, Punkt Tokenizer Models and Snowball Data.

**POS Tagger**

Download stanford POS tagger models here: http://nlp.stanford.edu/software/stanford-postagger-full-2014-08-27.zip
Unzip the archive and copy the related directory into the data directory.

## Load the notebook

Go to the notebook directory and run:

```bash
jupyter notebook
```

Then select the notebook in your browser.