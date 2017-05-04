# Predicting movie genres with deep learning

## Setup

All datasets needed to run our notebooks can be found [here](https://s3.amazonaws.com/109b/datasets.zip). We used several additional packages in the sentiment analysis section. We created a shell script that downloads and updates and required packages and sets up the datasets folder. The script can be found [here](https://s3.amazonaws.com/109b/get_datasets.sh) and running the following command should set everything up and start a Jupyter notebook session on the CS109b AMI with a token instead of a password:

```
wget https://s3.amazonaws.com/109b/get_datasets.sh && . get_datasets.sh
```
All milestone notebooks were submitted over the course of the project. The remaining notebooks were created for the final submission.

## Notebook Descriptions

- Milestone 1: initial data exploration
- Milestone 2: assembling training data
- Milestone 3: traditional methods
- Milestone 4: deep learning models
- Additional data exploration: metadata pairplots and sentiment boxplots
- Additional sentiment analysis: most frequent words in the TMDb dataset
- Genre frequencies: comparison between original and predicted genre frequencies
- Keras with metadata: deep learning models with movie metadata instead of posters
- Predictions heatmap: heatmap of predicted genres
