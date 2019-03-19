# passport-image-classifier
This project uses Tensorflow which is Google's Tensorflow's opensource library. I retrained one of their machine learning algorithms to classify real passport images and fradulent ones. This can be used for e-kyc technology for banks, airport checkups, sim-card registration etc.

Using the passport images from 15 different countries, I trained the model to detect "invalid" and "passport" with over 100,000 computations. The invalid category contains IDs other than passport such as national ID with or without MRZ reading, drivers licenses and specimen/fake passport files.

The classifier returns more than 90% probability for each of the test data tested. The document, “Sample Output” shows readings from 5 tests


The picture below shows the results of the accuracy of the model;


![screenshot](https://user-images.githubusercontent.com/18283171/54603995-a53cb800-4a80-11e9-93f9-e3a618854c0d.JPG)
