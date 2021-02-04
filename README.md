# How to reproduce ImageNet validation results

This code in this repository can be used to reproduce the [ImageNet validation results for Keras pretrained models](https://keras.io/applications/index.html#documentation-for-individual-models). A blog post describing this process in more detail is [here](http://calebrob.com/ml/imagenet/ilsvrc2012/2018/10/22/imagenet-benchmarking.html).

## Setup instructions

The ILSVRC2012 validation images should be put in `data/val/`. The remaining files mentioned in the blog post, and enumerated below, should be put in `data/`:
- `ILSVRC2012_validation_ground_truth.txt`
- `meta.mat`
- `synset_words.txt`

After the data is organized the notebooks can be run in order to reproduce model validation results.


