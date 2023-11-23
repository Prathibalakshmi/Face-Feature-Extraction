# Face-Feature-Extraction]
The face recognition system consists of a feature extraction step and a classification step. Principal component analysis (PCA) is widely used in such scenarios to construct the feature space and extract features, substantially reducing the dimensionality of the input feature vector/image. The reduced feature vector can then be used for the purpose of face analysis.

AIM:
Using PCA create a face recognition system that gives access to only certain people. To implement this, you can use LFW_peoples dataset provided in the scikit-learn library. Given this dataset, use only those classes that have a minimum (use min_faces_per_person = 70, resize = 0.4 ) 70 images (should give you only 11 classes). Given this subset of images, apply PA to obtain the corresponding eigen face for each class. You can additionally train a classifier for recognition purpose

Steps
- Import libraries
- Load LFW dataset
- Checking the size,shape,target name
- Extracting Data and labels
- Reshaping the images
- Perform PCA and plot the variance ratio
- Showing Eigen faces
- Transform data using PCA
- Train SVM classifier
- Checking the score
- Display the confusion Matrix
- Display original image and predicted image
