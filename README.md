This repository contains the solutions and related materials for the depth-estimation task for the AI mini-assessment.

The following was the introductory text with the requirements:

# The Task

## Assessment AI

Hi 👋😊

Here you will find, as discussed, the mini-task.

The deadline is the end of the 7th days (including the weekend) after receiving this mini-task. So if you received it on Monday, the deadline is next Monday, end of day.

Please create a private GitHub repository and share it with https://github.com/ZinelisCendas.

It should include:

a) Anything that is related to the answer of the task

b) The time you needed to complete the task

If you have any questions, please contact <ContactAtCendas>

### **Task**

**Techstack:** Python (scikit-learn/TensorFlow/PyTorch)

**Context:** consider the problem of Depth Estimation. The idea of this problem is to predict the distance to each pixel of an image. In such a way, the goal is to deliver a model that has an RGB image as an input (matrix of N x M x 3 values), and that outputs a matrix of depths (matrix of N x M x 1).

1. Implement any model and training + evaluation script on NYU Depth V2 (available in TFDS → https://www.tensorflow.org/datasets/catalog/nyu_depth_v2, so TensorFlow is probably better way to complete this assessment; but if you would prefer PyTorch, feel free to pick any Depth Estimation dataset that you may find). The model architecture should not be sophisticated or very complex, so feel free to pick any tiny architecture that should work from your point of view. The same for the training config and optimizer to use, but please demonstrate how to use different optimizers and callbacks, in particular learning rate scheduler.
2. Imagine right now that you are only limited to use scikit-learn for this task. What model will you pick and why? Implement the code that creates this model, train it on the data from TFDS NYU Depth V2 (some part of it that may fit into RAM), and evaluate it.
3. Now let’s do a little bibliographic research, and investigate if there are any ML/AI approaches publicly available with a ready-to-use implementation on GitHub. Short-list top 3 approaches that you succeed to find with values of key metrics on the most common datasets. Select among them the best approach from your point of view, figure out how to install and run it locally on GPU, make a step-by-step guide so that a person evaluating this assessment may follow this guide and run this approach on their end.

# Assumptions or clarifications

- Assume: supporting libraries are allowed (e.g. PyTorch vision, datasets, numpy, ...)
- Assume: For task 2, the model creation: "code that creates this model" - possibly from scratch? Clarify, assume or write both solutions (from scratch + imported if exists)
- Assume: MPS counts as GPU support (task 3); better to write form most common training case on Nvidia GPUs
- Assume: For part 3 the step-by-step guide is limited to one architecture (most common: Nvidia GPU)

# List of TODOs
- [ ] All material to complete task is included
- [ ] Time/work log for completion is included

### Part 1
- [ ] Model + training & eval script on NYU Depth V2 - arch as tiny as possible (as long as it does the job)
- [ ] Demonstrate use of different opts + lr schedulers

### Part 2
- [ ] Same task, limited to scikit-learn: Which model to choose + why? Implement code that creates the model, train on data from TFDS ... (the part that fits into RAM) + evaluate.

### Part 3
- [ ] short-list top 3 approaches publicly available on GitHub; include key metric comparison on common datasets
- [ ] select best of 3 (+ document decision), install + run locally with GPU support
- [ ] document (step-by-step guide) for person following assessment may follow & run on their end
