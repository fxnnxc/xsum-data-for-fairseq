# xsum-data-for-fairseq
make fairseq data structure for xsum


## Get the hugging face dataset 

You can find repo [here](https://github.com/huggingface/datasets)

```
git clone https://github.com/huggingface/datasets
pip install -e .
```

Then run the get_xsum.ipynb

## What you will get

```python
test.source 11334
test.target 11334
val.target 11332
val.source 11332
train.target 204045
train.source 204045
```
