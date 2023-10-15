# Text Torch - Information Retrieval from Documents

Document retrieval with natural language query against any given text dataset.

## Dataset 

We use simple english wikipedia dataset published from SBert. 
The dataset contains about 170K articles.
After we processed it, it produce ~500K samples.

References

- https://www.sbert.net/
- https://sbert.net/datasets

## Embeddings Models

`ms macro` - Asymmetric embeddings model build from real world search results of bing search engine.

https://www.sbert.net/examples/applications/semantic-search/README.html#symmetric-vs-asymmetric-semantic-search

## Model

kNN - K Neartest Neighbors utlizing `ms macro` embeddings vectors.