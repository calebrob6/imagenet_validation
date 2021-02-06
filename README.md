# How to reproduce ImageNet validation results

This code in this repository can be used to reproduce the [ImageNet validation results for Keras pretrained models](https://keras.io/applications/index.html#documentation-for-individual-models). A blog post describing this process in more detail is [here](http://calebrob.com/ml/imagenet/ilsvrc2012/2018/10/22/imagenet-benchmarking.html).

## Setup instructions

The ILSVRC2012 validation images should be put in `data/val/`. The remaining files mentioned in the blog post, and enumerated below, should be put in `data/`:
- `ILSVRC2012_validation_ground_truth.txt`
- `meta.mat`
- `synset_words.txt`

After the data is organized the notebooks can be run in order to reproduce model validation results.

=======
## Update 2/4/2021

- I was unable to find the ILSVRC2012 devkit online, so have included a copy of the 3 files (mentioned above) needed to run this in `data/` as well as the `COPYING` notice from the devkit [here](COPYING).
- I was able to reproduce these results with tensorflow=2.3.1 and keras=2.4.3 (see notebook 2)
