### Classify Song Genres from Audio Data

Welcome! This notebook focuses on classifying songs as either "Hip-Hop" or "Rock" based on audio data, and solely on musical features like *acousticness*. The dataset used is compiled by The Echo Nest and addresses the challenge of handling large music catalogs, commonly encountered in streaming services. This project demonstrates a step-by-step process to clean, preprocess, and reduce the dimensionality of the dataset using Principal Component Analysis (PCA), helping to visualize and capture the variance in the dataset. Finally, the processed data is classified using models like decision trees and logistic regression.

A general overview of the project:

- Analyzed the raw audio data from The Echo Nest to categorize and classify the music genres as "Hip-Hop" or "Rock" for personalized recommendations on streaming services
- Implemented dimensionality reduction through Principal Component Analysis (PCA) to reduce the number of features and prevent overfitting; performed exploratory data visualizations and resampling to remove bias from the class distribution, and construct a more balanced and robust model
- Applied systematic cross-validation and statistical methods to evaluate the model's performance and generalization capabilities, ensuring reliability and prevalence; this resulted in achieving an accuracy score of above 80% on the test set
