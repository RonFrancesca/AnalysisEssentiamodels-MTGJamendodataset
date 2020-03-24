# Analysis of Essentia models on the MTG Jamendo dataset

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

In order to run the notebook the following modules are necessary: numpy, essentia, json, sklearn, matplotlib.

All the module will be directly imported running the notebook.

Essentia will be installed directly running the notebook.

## Open the notebok in Google Colab

The notebook can be directly open from Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RonFrancesca/Analysis_Essentia_models-MTG_Jamendo-dataset/blob/master/LargeScale_Dataset_Classification.ipynb)

Read the Notebook instruction to properly change directories paths and run the notebook correctly.

All the data used in this work have been stored in Goodle Drive, so it can be mount directly from the notebook. 

## Clone or Download the repository 

If the user wants a local copy of the notebook, clone or download the reposiotry.
It contains a Google Colab notebook, please read the Notebook instruction to properly change directories paths and run the notebook correctly.

Command to clone the repository:
```
$ git clone https://github.com/RonFrancesca/Analysis_Essentia_models-MTG_Jamendo-dataset.git
```
Once the notebook is installed, open it from google colab and follow the instruction to configure it correctly. 

## MTG jamendo annotator 

More information about MTG jamendo annotator, how to configure it and run it can be found at the following link: https://github.com/MTG/mtg-jamendo-annotator. 

## MTG jamendo dataset 

More information about the MTG jamendo dataset can be found in the following paper. 

> Bogdanov, D., Won M., Tovstogan P., Porter A., & Serra X. (2019).  [The MTG-Jamendo Dataset for Automatic Music Tagging](http://mtg.upf.edu/node/3957). Machine Learning for Music Discovery Workshop, International Conference on Machine Learning (ICML 2019).

The dataset can be found at the following links: https://github.com/MTG/mtg-jamendo-dataset

## Tenworflow models for Essentia 

The models used for this work can be downlaoded at the following link: https://mtg.github.io/essentia-labs/news/2020/01/16/tensorflow-models-released/. 
For this work, two tasks have been examinated (mood and miscellanous). 
The following models have been considered: 
- Mood task: MusiCNN_MSD and VGGish_AudioSet
- Miscellanous task: MusiCNN_MSD and VGGish_AudioSet


## Author 
- Francesca Ronchini


