# APAI-LAB02: DNN Definition and Training

## Material

- Slides: [here](./_docs/slides.pdf)
- Notebook (assignment): [here](./APAI26-LAB2-DNN-definition-and-training.ipynb)

## Summary

In this lab we will define and train a simple Convolutional Neural Network (CNN) with PyTorch, working inside a Jupyter notebook. The slides introduce the building blocks of CNNs (convolution, batch normalization, ReLU, softmax, max pooling, dropout); the notebook then guides you through using them to build a network and train it on the [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist) dataset.

The assignment is contained entirely in the notebook. Each task comes with its own resources, sub-tasks and tips:

1. Creating a model
2. Count the network's parameters and MAC operations
3. Dataset & DataLoaders
4. Testing the CNN over the dataset
5. Training loop
6. Save/load model

Guidelines to work on today's assignment:

1. Read the [slides](./_docs/slides.pdf)
2. Set up the environment, preferably on Google Colab, or locally in VS Code (see [Quickstart](#quickstart))
3. Complete Tasks 1-6 in the [Jupyter notebook](./APAI26-LAB2-DNN-definition-and-training.ipynb)

**AI policy:** we will not prevent you from using AI to solve the assignments, but the lab is meant to be a hands-on learning experience. To keep it useful, this repository includes an [AGENTS.md](./AGENTS.md) file (also used in a Stanford class) that AI agents should read automatically, so that they guide you towards finding the solution yourself instead of giving it to you directly.

## How to deliver the assignment

1. Run all the cells and save the notebook, so that the results show up in the cells. Do **NOT** clear the outputs of the cells.
2. Rename the notebook to `LAB2_APAI_<name_surname>.ipynb`
3. Upload it to Virtuale:
    - If you run on Colab, download it first (`File → Download → Download .ipynb`), then upload it
    - If you run locally, upload the saved notebook directly from your PC

For each lab that you solve and submit successfully, you will receive 1 extra point, up to a maximum of 4 points.

**Assignment DEADLINE: Sunday, 25/10/2026 (at 23:59)**

___

## Quickstart

**This lab must be run on your own personal computer**, since the lab machines have very limited internet access, which doesn't allow you to access Google Colab or to download the necessary libraries.

There are 2 ways to complete the assignment. We recommend Google Colab:

### Option 1 (preferred): Running on Google Colab

[Google Colab](https://colab.research.google.com/) runs Python notebooks in the cloud and is accessed via your browser, so it should work on any system.

1. Download the notebook, either from Virtuale or by cloning this repository
2. Open Google Colab and choose the "Upload notebook" ("Carica notebook") option
3. Use the pop-up to upload the notebook that you just downloaded
4. Now you're ready to start!

### Option 2: Running locally, in VS Code

1. Clone this repository:
```
git clone https://github.com/EEESlab/APAI26-LAB02-DNN-definition-and-training
cd APAI26-LAB02-DNN-definition-and-training/
```
2. Open the notebook in VS Code. It should work with minimal setup: if any component is missing (e.g., the Python or Jupyter extensions, or the kernel), VS Code will direct you to install it.
3. Now you're ready to start!
