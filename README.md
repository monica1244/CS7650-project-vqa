## Visual Question Answering
#### Course Project for CS 7650: Natural Language Processing (Prof. Diyi Yang) @ Georgia Institute of Technology

### The Project
As part of our graduate NLP course, we experimented with novel methods of performing Visual Question Answering and designed 4 models for the task. A detailed description of our methodology can be found in the NLP_Final_Report file in this repository.

### Data
1. Dataset consists of ResNet-18 Image features, Tokenised Questions, Tokenised Answers (in Numpy format): https://drive.google.com/open?id=1DCHNVK5pxAKOiiJcfMGcO-pSjJDIv1zT
2. Dataset containing Image locations, Question and Answers can be found in the dataset directory. 
3. For generating VGG-16 Image features needed by Parallel and Alternate Co-Attention, Fusion and Co-Attention model use the Python notebook named DataCreationVGG.
4. Raw Images for dataset (needed for creating VGG-16 Image features): http://images.cocodataset.org/zips/train2014.zip, http://images.cocodataset.org/zips/val2014.zip

### Models
1. Fusion Model: Run Trainer.ipynb with default settings
2. CNN + LSTM Model: Run Trainer.ipynb and change fusion_type to Concatenation
3. Parallel and Alternate Co-Attention Model: Run ParallelAndAlternateCoAttention.py
4. Fusion and Co-Attention Model: Run FusionAndCoAttention.py

### Model Weights
Trained Weights for all models: https://drive.google.com/open?id=1dMvJ9bQlIhEHjr_zw5uL6KLuGJfKpfqs

### Contributors
Divyansh Kumar Roy @ https://github.com/DivyanshRoy<br>
Shubhangi Upasani @ https://github.com/ShubhangiUpasani<br>
Monica Gupta @ https://github.com/monica1244<br>

### Project Video
Video hosted at https://drive.google.com/open?id=1vwYaNXBy7Gq5jYjZxcR8lEQujti8MLAb

This repository is a copy of the original project repository hosted at: https://github.com/DivyanshRoy/CS7650-project-vqa
