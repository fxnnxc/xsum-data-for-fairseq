# xsum-data-for-fairseq
make fairseq data structure for xsum

<p align="left">
  <img src=https://img.shields.io/badge/Python-v3.6.8-green?style=flat&logo=python height=30px></a> 
</p>

## Get the hugging face dataset 


This data structure based on huggingface datasets .

You can find repo [here](https://github.com/huggingface/datasets)

```
pip install datasets

or

git clone https://github.com/huggingface/datasets
pip install -e .
```

Then run the get_xsum.ipynb

## What you will get

```python
file         #lines
test.source  11334
test.target  11334
val.target   11332
val.source   11332
train.target 204045
train.source 204045
```
