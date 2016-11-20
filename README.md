# PySummarize
PySummarize is a python library that allows you to perform automatic text summarization using word frequency and sentence position.

# Usage
Import the class PySummarize:
```python
   from pysummarize import PySummarize
```
Instantiate a PySummarize object and Use the 'summarize' method to produce a summary:  
```python
   text = "This is the text you want to summarize..."
   ps = PySummarize()
   # create a summary which is at most 100 words long  
   summary = ps.summarize(text) 
```
Optionally, you can specify the max length of the summary in no. of words passing it as the second argument of 'summarize' 
```python
   ...
   # create a summary which is at most 100 words long  
   summary = ps.summarize(text, 100) 
```


# Installation
To install PySummarize, use the following code:
```python
   pip install pysummarize
```
# Dependencies
You need to have the NLTK library installed to use PySummarize.
