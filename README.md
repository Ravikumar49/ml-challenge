Input feature: 47 numerical features representing specific operational parameters, internal
    states and performance metrics
Target Varible: A binary classification label indicating the device's status.
    0: Normal condition
    1: Faulty

Approach: To maximize both Accuracy and F1 Score, I implemented XGBoost Classfier. It was choosen because gradient boosting algorithms typically yield the highest performance for dense numerical sensor data. The model was trained with specific hyperparameters (like controlled learning rate, max depth, subsampling) to prevent overfitting and ensure model generalizes well to unseen data.
