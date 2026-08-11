# IDS-against-DDoS-Attacks-using-SHAP-feature-selection-HTS-with-Dense-MLP
Part of M.Tech Mini-Project used CICDDoS2019 dataset for the experimentation

Designed and Evaluated a `deep learning-based IDS` that focuses on DDoS network attacks using a popular dataset.

To strengthen the model’s performance, we have used the `Shapley feature selection method` with the `Hotelling T2 Test` to choose the top contributing set of features, which contribute the most in deciding whether there is an attack or not.

By feature selection method reduced the original `87` features to the `21` most predictive attributes. 

After selecting the features, used a `dense multilayer perceptron (MLP)` - a deep learning model well-known for recognising complex data patterns. 

The model was trained and tested on the optimal dataset to differentiate benign and DDoS network attacks. 

Evaluated its performance using metrics like `accuracy`, `recall`, `precision`, `balanced accuracy` and `F1-score`. 

And also, it gives highly accurate detection of DDoS network attacks with a `low False Positive` and `True Negative`. 

The results demonstrate that integrating meaningful feature selection with deep learning strengthens IDS performance and offers a practical, interpretable, and computationally efficient solution for real-time DDoS detection.
