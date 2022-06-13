# Bank Marketing Classification
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. 
Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 
This Dataset as well as further informations about it can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

# Data
The Dataset is highly imbalanced, out of the 41188 answers only about 10% or 4640 of the answers were positive. Apart from that, the data does not contain any missing values.

# Goal 
Create a classification model to predict clients answers.


# Result 
Since the data is highly imbalanced vanilla algorithms performed badly. Luckily the class weight of the classifiers can set to "balanced weight",
which improve the predictions significantly, as seen in the table below. The results are based on testing the algorithms solely on the training data.

![Summary](https://user-images.githubusercontent.com/70484577/173445279-f9f8a1f4-6354-4643-903a-5bb44f2d172e.JPG)

Best algorithm performance on the test data.

![best_alg](https://user-images.githubusercontent.com/70484577/173446386-a0a33806-d5da-41d7-b5c7-15c344018c8a.JPG)
