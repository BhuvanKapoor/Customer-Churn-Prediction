📊 Churn Prediction using Artificial Neural Networks (ANNs)

📚 Project Overview
This project aims to predict customer churn using Artificial Neural Networks (ANNs). Customer churn is a significant challenge for businesses, and accurately identifying customers at risk of churning can enable targeted retention strategies.

📄 Dataset
The dataset used in this project includes information about client activities, sales channels, electricity and gas consumption, and other relevant features. The dataset comprises 14,606 entries with 26 columns.

🔬 Exploratory Data Analysis (EDA)
The EDA process involved analyzing the distribution of client activities, sales channels, consumption patterns, and other key variables. Additionally, the EDA explored relationships between factors such as churn, pricing, taking gas supply, and power subscribed.

🛠️ Feature Engineering
The project involved several feature engineering steps, including:

Converting date columns to datetime format
Calculating the difference in off-peak prices between December and the preceding January
Aggregating average price changes across different pricing periods
Calculating the maximum monthly price changes across periods
🧠 Model Development
The project used an Artificial Neural Network (ANN) model to predict customer churn. The model was built using the Keras library in Python and consisted of several hidden layers with ReLU activation functions and a final output layer with a sigmoid activation.

📈 Model Evaluation
The ANN model achieved an accuracy of 90% on the test set. The classification report and confusion matrix were used to further analyze the model's performance.

📝 Conclusion
This project demonstrates the potential of Artificial Neural Networks in predicting customer churn. The insights gained from the EDA and feature engineering process can help organizations better understand the factors influencing customer churn and implement targeted retention strategies.

🔮 Future Improvements
Potential areas for future improvement include:

Exploring additional feature engineering techniques
Experimenting with different ANN architectures and hyperparameters
Incorporating other machine learning models for comparison
Analyzing the model's performance on new, unseen data
🛠️ Usage
To run this project, you will need to have the following dependencies installed:

Python 3.11.8
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
TensorFlow/Keras
You can clone the repository and run the Jupyter Notebook or Python script to reproduce the analysis and model development.

Edit
Full Screen
Copy code
git clone https://github.com/BhuvanKapoor/Customer-Churn-Prediction.git
🤝 Acknowledgments
This project was completed as part of a data science course or personal learning endeavor. The dataset used in this project is not publicly available but was provided as part of the course or project requirements.