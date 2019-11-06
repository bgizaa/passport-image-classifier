# passport-image-classifier
This project uses Tensorflow which is Google's Tensorflow's opensource library. I retrained one of their machine learning algorithms to classify real passport images and fradulent ones. This can be used for e-kyc technology for banks, airport checkups, sim-card registration etc.

Using the passport images from 15 different countries(mostly found online), I trained the model to detect "invalid" and "passport" with over 100,000 computations. The invalid category contains IDs other than passport such as national ID with or without MRZ reading, drivers licenses and specimen/fake passport files.

The classifier returns more than 90% probability for each of the test data tested. The document, “Sample Output” shows readings from 5 tests


The picture below shows the results of the accuracy of the model;


![screenshot](https://user-images.githubusercontent.com/18283171/54603995-a53cb800-4a80-11e9-93f9-e3a618854c0d.JPG)


## Helpful Resources to retrain your own object-detection models

https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/?utm_campaign=chrome_series_machinelearning_063016&utm_source=gdev&utm_medium=yt-desc#3

https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10#appendix-common-errors

## Setting up

```
pip install --ignore-installed --upgrade tensorflow-gpu
```

