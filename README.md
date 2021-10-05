# Principles of Biological Vision
---
### Course Assignment
---
##### Author:
Umang Barbhaya 
M20CS017

##### Course Instructor: 

Dr. Hiranmay Ghosh\
Guest Faculty\
Department of Computer Science & Engineering\
Indian Institute of Technology, Jodhpur

---
#### Assignment-1: Modeling Early Vision
Report has been attached inside Assignment-1 Folder\
Below are the steps which were done\
- Took two images as given by the Instructor and did some preprocessing on it.
- Created a DoG filter for emulating the lateral inhibition. Applied this filter on the images and recorded the results in report.
- Created oriented filters (0, 45, 90 and 135 degree) using gabor filter for detecting the oriented edges. This filter was applied on DoG filtered image.
- Superimposed the edge images by applying the WTA policy and normalization for reproducing the outlined image.

#### Assignment-2: Implementation of Bayesian network
Report has been attached inside Assignment-2 Folder\
Below are the steps which were done\
- Implemented the bayesian network as per the network graph, initial prior probability and conditional probability table given by the instructor.
- Kept some values default and observed the changes happening in the network. Changes have been recorded inside the report.
- Also, Explained the reason behind the changes

#### Assignment-3: Spatial Envelop Representation
Report has been attached inside Assignment-3 Folder\
Below are the steps which were done\
- Took 20 images as as given by the Instructor and did some preprocessing on it.
- Created a DoG filter for emulating the lateral inhibition as in Assignment 1. Applied this filter on the images and recorded the results in report.
- Computed the global edge histogram for (0, 45, 90, 135 and no edge as per the WTA policy).
- Observed the four oriented edge orientation maps and the corresponding histograms for a few forest and city images, and mentioned in report my findings and Observations
- Applied k-means clustering algorithm (Cluster size k=2) on the histograms, and showed the images in each cluster separately.
