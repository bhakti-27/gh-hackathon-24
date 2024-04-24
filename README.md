# Overview

Project: Developing a computer vision model to identify diseased and dead trees in forested areas using Landsat data.<br>
Purpose: To provide a rapid and efficient method for Federal, state, and local land managers to identify and respond to tree disease and mortality, reducing hazards from untreated trees and facilitating early detection of invasive species outbreaks.
Audience: Federal, state, and local land managers, utility foresters, asset managers, arboriculture consultants, and regulators, with the goal of improving forest management, reducing the risk of power outages and forest fires, and containing the spread of invasive species.<br>

# The Model
The ImageNet feature representation was established using images of bands and time for classification. Logistic basic regression was used to classify pixels with partial fit. Model performance was evaluated by randomizing pixel representations and retraining the model. RSME increased as expected when data was randomized at the pixel/time series stage

Finally, we visualized our model output, error and ground truth using matplotlib and wrote the asset as a geotiff.
<img src = forest_pick.png width="750" height="320"/>

<br>

# Model Pipeline
<img src = transfer_learning.PNG width="750" height="300"/>
<br> 

# Set Up
Please obtain imagery data from the source of your choice and either 1) retrain the models or 2) use the pretrained models.
