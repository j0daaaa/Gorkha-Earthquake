# Gorkha-Earthquake
Writers:
- Jonathan David
- Vira Jessica

Earthquake is a natural phenomenon caused by the Earth’s tectonic movement, causing the ground to shake. The unpredictability of earthquake itself creates vulnerability towards the residents living in the seismic zones, especially in areas where urbanization is rapidly increasing. Driven Data provided us with data containing the damage levels to the buildings in Gorkha post the Gorkha Earthquake in 2015, which occurred in Nepal. Thus, we conducted an analysis of the data in order to build predictive models to estimate the damage level to buildings in Gorkha post earthquake. We also calculated the F1-score micro for each model, representing the accuracy in classification.

In our data pre-processing phase, we transformed categorical features into numerical representations using label encoding, applied data scaling, and split the dataset into training and testing sets. We evaluated several machine learning models suitable for classification tasks, including a Feedforward Neural Network (FNN), Random Forest (RF) with Grid Search Cross-Validation (GSCV) for hyperparameter tuning, and Light Gradient-Boosting Machine (LightGBM) with GSCV. Each model was trained on the label-encoded training data. To assess performance, we compared the micro-average F1 score derived from these models, ensuring a robust evaluation of their effectiveness.

We found that the LightGBM model outperformed both the (FNN) and (RF) with Grid Search Cross-Validation (GSCV) in terms of the micro-average F1 score. Additionally, we identified the most important features that significantly impact the target label, "geo_level_id." These findings and methodologies are thoroughly documented in this [project paper](https://drive.google.com/drive/folders/1vQ5VHuHy7wehHi3C98GeJX9gxRbzCZ36?usp=drive_link).
