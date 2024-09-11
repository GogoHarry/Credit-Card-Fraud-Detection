# Credit-Card-Fraud-Detection
This project focuses on developing a high-performance, scalable, and accurate machine-learning model to detect and prevent fraudulent credit card transactions in real time. The solution employs advanced data preprocessing techniques and classification algorithms, ensuring precision and efficiency in identifying fraudulent activities.

## Project Overview
![card](https://github.com/user-attachments/assets/d2789b27-3317-4340-bec3-2f2dd64676bc)

This project aims to predict fraudulent transactions in a credit card dataset. Class imbalance is a key challenge, and various machine learning algorithms were applied to handle this, with XGBoost showing the best performance.

### Key Metrics:
- Accuracy: 99.94%
- Precision (Fraudulent class): 0.88
- Recall (Fraudulent class): 0.79
- F1-Score (Fraudulent class): 0.83
- ROC AUC Score: 0.9653

## Models Used
- **Logistic Regression:** Used as a baseline model.
- **Random Forest:** Applied with balanced class weights to address the class imbalance.
- **XGBoost:** Used with class imbalance handling and showed superior performance.

## Results
XGBoost outperformed other models with the following performance metrics:

![image](https://github.com/user-attachments/assets/a8013701-50e5-4c2b-8e48-2a826dcbc4ff)

## Instructions
To replicate this project:

1. Clone the repository:
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
```
2. Install the required libraries:
```bash
pip install -r requirements.txt
```
3. Open and run the Jupyter notebook:
```bash
jupyter notebook credit_card_fraud_detection_model.ipynb
```
## Conclusion
XGBoost showed the best performance with an accuracy of 99.94% and a strong ROC AUC score of 0.9653, making it the most effective model for detecting fraudulent transactions.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License
This project is licensed under the Apache-2.0 license - See the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to the contributors and the open-source community for their invaluable support.

