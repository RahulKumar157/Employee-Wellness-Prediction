# Employee-Wellness-Prediction

   Data Preprocessing
Encoded categorical features using One-Hot Encoding to ensure numerical representation.
Ensured consistency between training (X_train) and test (df_test) datasets.
Handled missing categories by adding absent columns in df_test with a default value of 0.
Applied scaling to numerical features for better model performance.
   Model Training
Trained a Machine Learning Model (e.g., RandomForest, XGBoost, Logistic Regression).
Evaluated performance using Accuracy, Precision, Recall, and F1-score.
Selected the best threshold for classification using the Precision-Recall Curve.
   Predictions & Threshold Optimization
Predicted probabilities for df_test.
Applied an optimized threshold instead of the default 0.5 for better classification.
   Convert Predictions to Yes/No
Converted model outputs (0 and 1) into "Yes" and "No" for easier interpretationStep 5: Save Final Predictions
Saved the results in submission.csv, ready for hackathon submission.
   Final Outcome
Successfully predicted whether a person needs treatment ("Yes"/"No") based on given features.
The submission file is now complete and ready for evaluation.
