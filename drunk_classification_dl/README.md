
## Challenges and approaches
1. The size of dataset is very small **->** Using transfer learning (with pretrained InceptionV3 model), along with augmentation.
2. Four fundamentally different images are given for classification to single class. **->** Still need to workon to utilize all four.
3. The images are single channel IR images, which are difficult to use with pretrained models. **->** Creating 3 channel images by repeating the same image over.

## Executing the program
* At the current level, only face images are used to classify a person as sober or drunk.

### Formatting the dataset for use in classification
* Copy __CV_problem_sober_drunk_database__ folder inside the repository.
* Execute all the cells in __dataset_creation.ipynb__

### Working with classifier
* Execute the cells in __drunk_classifier.ipynb__ (More details are provided inside each cell).

## Results
* After training and validation, received __87.5% accuracy on testset__. (Results can be seen in last cell of __drunk_classifier.ipynb__)