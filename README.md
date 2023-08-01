# Modified-Human-Sperm-Morphology-Analysis

## Meta-Learning for Human Sperm Abnormality Detection

In this project we had made a model and detected human sperm's head, vacoule, acrosome, and tail abnormality using Meta-Learning.      

## Dataset
This was done on [MHSMA](https://data.mendeley.com/datasets/hjygss6sw2/2) dataset.

The MHSMA dataset is a collection of human sperm images from 235 patients with male factor infertility. Each image is labeled by experts for normal or abnormal sperm acrosome, head, vacuole, and tail.       
The training, validation, and test sets contain 1000, 240, and 300 images, respectively.        
Images are available in two different crop sizes: 128x128- and 64x64-pixel.       

## Approaches
We used MAML algorrithm in [Learn2Learn](https://learn2learn.net/) and Pytorch libraries.       

MAML, or Model-Agnostic Meta-Learning, is a model and task-agnostic algorithm for meta-learning that trains a model’s parameters such that a small number of gradient updates will lead to fast learning on a new task.     


## Team members
  1. Amir Kasaei
  2. Amir Ezzati
  3. Amin Daemdoost