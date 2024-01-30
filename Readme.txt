Crop Type Classification using Remote Sensing Imagery and Machine Learning

This project focuses on crop-type classification using remote sensing imagery and machine learning techniques. The goal is to provide accurate and up-to-date information on the spatial distribution of crops to aid in agricultural planning and decision-making. The study uses Sentinel-2 imagery from the 2019 cropping season, covering four main crops in Mali. The machine learning models employed include Random Forest and Neural Networks, with a comparative analysis of their performance.

Dataset Description

The dataset is sourced from Radiant MLHub and consists of Sentinel-2 time-series images covering the 2019 growing season in Mali. It includes 33 fields, each with 41 images, capturing the temporal and spatial resolution of the Sentinel-2 constellation. The target classifications are segmented into five classes: no data, millet, maize, sorghum, and rice.

Results and Discussion

The results indicate high accuracy in classifying the "no data" segment but poor accuracy for targeted crop segments. Random Forest outperforms Neural Networks slightly. Future works aim to improve accuracy by applying noise filtering, fusion of different features and bands, hyperparameter tuning, and the application of transfer learning.