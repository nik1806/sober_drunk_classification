## Task

The task is to build a classifier that can classify for a given image as sober or mild drunk or drunk.  In order to train or test, u can consider all four, front, side etc. at once to classify  whether drunk or sober.

## About dataset

Attached is the data of 41 people, taken from IR sensor. For each person, there are 4 types of images taken: sober, 20 mins after drinking, 40 mins after drinking, 1hr after drinking 4 glasses of wine. For each type for each person, 4 images are taken: front face, side face, eyes, and hand palm.

## Installing dependencies

I have used virtual environments for handling the dependencies. Run the following command:

```
pip install -r requirements.txt
```

## About the repo

* This repository explores and presents 2 different approaches to tackle the problem.
1. Using transfer learning - based on concepts of deep learning - achieving an accuracy of 87.5% (More details inside __drunk_classification_dl__ directory).
2. Using rudimentary methods of feature extraction and separate classifier - based on classical machine learning - achieving an accuracy of 58% (More details inside __drunk_classification_ml__ directory)