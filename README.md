## PIR-based Human Activity Recognition

* Developed deep learning models to classify human presence and activity states using synchronized Low-Energy PIR sensor data.
* Processed dataset of **7,651 instances** with 56 features; applied **SMOTE** for class imbalance and **StandardScaler** for normalization.
* Engineered robust feature set from PIR signals and temperature readings; excluded timestamps to improve performance.
* Designed and trained **MLP, GRU, and LSTM architectures**, with **LSTM achieving 99.62% validation accuracy** and **0.9958 Macro F1-score**.
* Implemented **5-Fold Stratified Cross Validation**, tracking precision, recall, F1-score, and confusion matrices to ensure model robustness.
