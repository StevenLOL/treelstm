These code contain treelstm for Chinese, using sick (one vs one similarity) as starting point. 

1) you need download related models for Chinese

eg:
stanford-chinese-corenlp-2016-01-19-models.jar

http://nlp.stanford.edu/software/stanford-chinese-corenlp-2016-01-19-models.jar

2) when build the "class" file, you need the corenlp as well, you can also download it from standford.

http://stanfordnlp.github.io/CoreNLP/history.html

When the "class" build sucessfully then copy them to the treelstm/lib folder, and update script/preprocess-sick.py

The replace the sick data with the data you have.


Done.
