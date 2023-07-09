# Wildfire-burn-scars-detection-in-Alaska

This is a study about wildfire burn scars in Alaska with 2 main parts.

In the first part, the climate factors contributing to the cause of wildfires in Alaska for the study period 2001-2019 are explored. This section will introduce the following techniques: Pearson correlation coefficient, Spearman correlation coefficient, Kendall correlation coefficient, linear regression, and crosscorrelation analysis.

Two different machine-learning models for identifying wildfire burn scars are employed in the second part: built from scratch UNet model and pretrained UNet model (with ResNet101 encoder). The training dataset for these models includes 75 images/mask pairs from Sentinel-2, where each image includes in itself 6 bands (red, green, blue, NIR, NDVI, NDMI).

Links to datasets are provided in the Jupyter Notebook "Wilfire burn scars in high latitudes", to download exactly the same dataset the following link should be used:
https://drive.google.com/drive/folders/1sjAVfdW2iVNbKdUqt6pjy97WGtA1EJrV?usp=drive_link
