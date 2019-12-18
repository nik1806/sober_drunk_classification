
## Challenges and approaches
1. The size of dataset is very small.
2. Four fundamentally different images are given for classification to single class. **->** Features of all four images are stacked horizontally
3. Finding out the type of features to extract is challenging.

## Executing the program (classical ML approach)
* At the current level, all four images are used to classify a person as sober or drunk, but taken from set 1 and 4.

### Attempt to analyze the image
* In __image_hist.ipynb__ an intuitive attempt to analyze the intensity of pixels using histogram is performed.

### Extracting features from the dataset for use in classification
* Copy __CV_problem_sober_drunk_database__ folder inside the repository.
* Execute all cells in __dataset_creation.ipynb__ to segregate images for further use.
* Execute all the cells in __feature_extractor.ipynb__ then

### Running of classifier
* Execute all the cells in __svm_classifier.ipynb__ (More details are provided inside each cell).

## Results (ml)
* After training and validation, received __57.8% accuracy on testset__. (Results can be seen in last cell of __drunk_classifier.ipynb__)
