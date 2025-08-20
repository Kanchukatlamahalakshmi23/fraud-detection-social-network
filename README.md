# fraud-detection-social-network
## Introduction
This project is a machine learning system designed to detect and classify fraudulent users in mobile social networks. The goal is to identify fake accounts early by analyzing their network behavior and interactions, addressing a growing problem on social platforms.

## Tech Stack
* **Languages:** Python
* **Libraries:** Pandas, Scikit-learn, NetworkX, Seaborn
* **Tools:** Jupyter Notebook, Git

## Project Breakdown
* **Data Preprocessing:** Cleaned and preprocessed a dataset of user interactions to prepare it for analysis.
* **Graph Analysis:** Constructed a user interaction graph using NetworkX to model social connections and identify community patterns associated with fraud.
* **Model Development:** Developed and trained machine learning models (Decision Tree, Logistic Regression) to classify users.
* **Evaluation:** The final model was able to classify users with an accuracy of 85%.

## How to Run This Project
1. Clone the repository: `git clone https://github.com/your-username/fraud-detection-social-network.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the main Jupyter Notebook: `jupyter notebook main.ipynb`
