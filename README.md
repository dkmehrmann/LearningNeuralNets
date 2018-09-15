# LearningNeuralNets

Learning Neural nets through fun, interactive examples instead of dense, complicated math notation.

## Purpose

Math is a concise way to explain complicated concepts (like neural nets), which is why so many neural net tutorials look like PhD theses. I intent to give a math-light, natural language overview of neural nets for people who suck at math, like me.

SEO: Deep Learning, AI, Machine Learning, Python, Neural Network, DNN, CNN, RNN



## My AWS Notes:

### Launch Instance
* Choose My AMIs: `my_DL_image`
* security group: `my_aws`
* keypair: `my_aws_real`

### SSH
* ssh `ubuntu@<Instance Public DNS>`

### Operation
* `bash startup.sh` will clone the repo and launch a notebook server
* copy the URL from the prompt but replace `0.0.0.0` with the instance's public DNS