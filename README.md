Docker image that contains the **[gensim](https://radimrehurek.com/gensim/) Python library** ("topic modelling for humans").

The image is **based on Ubuntu and Python3**, so use the *python3* command, not *python*.

The image contains the fast version of **doc2vec** (written in C).

**What is Gensim?**

Gensim is a FREE Python library
* Scalable statistical semantics
* Analyze plain-text documents for semantic structure
* Retrieve semantically similar documents

**How to run it**

```
docker run -it --rm zmarty/python3-gensim-doc2vec
```

If you are new to Docker, please note that due to the rm command line argument above all your file changes within the container will be lost.
