# Neural-Network-Compression
Modification on caffe source model to compress Lenet-5.
## Results
The model after fine tuning shows a great decrease in the number of parameters. The original model takes about 1720KB memory for parameters storage, while the compressed model only takes about 44KB. The compress rate is nearly 40×. However, the accuracy doesn't decrease. It reaches about 99.06\% when tested on MNIST dataset to identify handwriting digits.

details see /statement/main.tex
