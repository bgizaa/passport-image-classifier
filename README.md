# passport-image-classifier
Using the passport data I had from about 15 countries, I trained the model to detect "invalid" and "passport". The invalid category contains IDs other than passport such as national ID with or without MRZ reading, drivers licenses and specimen/fake passport files. The classifier returns more than 90% probability for each of the test data in the folder. The document, “Sample Output” shows readings from 5 tests.

below shows the results of the accuracy of the model.
![screenshot](https://user-images.githubusercontent.com/18283171/54603753-1af45400-4a80-11e9-8b56-dfa724d96613.PNG)
