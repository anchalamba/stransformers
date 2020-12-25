# stranformers
## Environment setup

Setup pyenv using [this article](https://opensource.com/article/19/6/python-virtual-environments-mac)

```bash
# setup a Python3 virtual environment
pyenv global 3.8.6
mkvirtualenv stransformers
# OR
virtualenv stransformers -p `which python3`
```

## Simple Transformers

A wrapper on Hugging Face to simplify model training steps

### T5 Small Example

Used [this blog post](https://towardsdatascience.com/asking-the-right-questions-training-a-t5-transformer-model-on-a-new-task-691ebba2d72c) for training a new task with T5 small, referring to [this git repo](https://github.com/ThilinaRajapakse/simpletransformers/tree/master/examples/t5/training_on_a_new_task)

Install the following packages, corresponding to the conda list/env [here](https://simpletransformers.ai/docs/installation/)

```bash
# ------------------------------------------------------------------------------
pip install pandas tqdm
pip install torch torchvision
pip install simpletransformers
pip install jupyter
```

Adapted from [Thilina Rajapakse's code](https://github.com/ThilinaRajapakse/simpletransformers/tree/master/examples/t5/training_on_a_new_task) to create a custom Jupyter notebook for our passive to active conversion task:`p2a_T5_small.ipynb`

