# Transformer NLP

The goal of this repo is to reimplement the transformer. A few useful resources:
- http://nlp.seas.harvard.edu/annotated-transformer/
- https://blog.floydhub.com/the-transformer-in-pytorch/
- https://www.youtube.com/watch?v=kCc8FmEb1nY - Build GPT by Andrej Karpathy

This is a character-level transformer based mostly in the last resource above. To use it you need to:
- install poetry
- clone this repository
- install the dependencies with `poetry install`
- run `poetry run python transformer_nlp/bigram.py` from the root directory. 


You can room the bigram model easily on a CPU. The transformer.py model trains in roughly 20 minutes on a Nvdia 2080 Titan RTX GPU. 