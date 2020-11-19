#PhysioBank ATM scraper to get ECG data and build an automatic anomaly detection model using LSTM-Autoencoders for clustering

The PhysioBank ECG ATM, maintained by MIT, is notoriously hard to scrape as it is designed to block users from accessing the site as soon as it detects any sort of automation. To this end, I have written a scraper in order to get ECG data from the ATM, after which I use an LSTM autoencoder in order to encode the data and cluster them later for automatic anomaly detection. This repository currently contains code upto the Autoencoder step.
