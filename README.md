# Predicting LeBron James' Shot Success

This project aims to predict the success of LeBron James' basketball shots (made vs. missed) using historical NBA shot logs from the 2004 to 2024 seasons. Advanced feature engineering, statistical modeling, and machine learning algorithms were applied to uncover patterns in the data and build predictive models.


---

## **Dataset**

DataSet Link : https://github.com/DomSamangy/NBA_Shots_04_24

---

## **Features of the Project**

- **Dataset**: NBA shot logs containing over 4 million rows, filtered to focus on LeBron James.
- **Feature Engineering**: Grouped shot zones, action types, and spatial features to create meaningful features.
- **Models Used**:
  - Logistic Regression
  - Random Forest
  - XGBoost
- **Performance Metrics**: Evaluated using accuracy, precision, recall, and AUC-ROC.

---

## **Installation and Setup**

### **Clone the Repository**

```bash
git clone <repo_url>
cd <repo_directory>
```

### **Install Dependencies**

Ensure you have Python 3.8 or higher installed. Use the `requirements.txt` file to set up the environment:

```bash
pip install -r requirements.txt
```

---

## **How to Run**

### **Jupyter Notebook**

1. Open the notebook:
   ```bash
   jupyter notebook shot_prediction.ipynb
   ```
2. Follow the step-by-step instructions in the notebook to:
   - Preprocess the dataset.
   - Engineer features (e.g., grouping action types and zones).
   - Train and evaluate models.

### **Key Outputs**

- **Feature Importance Visualization**: Highlights the most impactful features in predicting shot success.
- **Model Performance Metrics**: Compare the accuracy and AUC-ROC of different models.
- **Insights**: Understand patterns in shot success, such as the high impact of close-range zones and action types like dunks.

---

## **Project Highlights**

### **Data Preprocessing**

- Filtered data to focus on LeBron James' shots.
- Normalized and encoded categorical variables.

### **Modeling**

- Logistic Regression: Found the most interpretable features and their coefficients.
- Random Forest: Leveraged its ability to capture non-linear relationships.
- XGBoost: Achieved the highest accuracy and AUC-ROC through advanced hyperparameter tuning.

---

## **Insights**

- **Top Positive Features**:
  - Shots from the `Restricted Area` and `Central Zones` have the highest success rates.
  - Close-range actions (e.g., dunks, layups) strongly impact shot success.
- **Top Negative Features**:
  - `SHOT_DISTANCE` and backcourt shots significantly reduce success rates.
- **Actionable Insights**:
  - Focus on high-probability zones for better decision-making during games.

---

## **Video Overview**

A 1 minute video summarizing the project is available. It highlights the methodology, findings, and applications of this analysis. The video is suitable for presentations and showcases key results visually.

Link : https://youtu.be/ZBgakvKKvIg?si=Etv3Em6yVtxx44vj

---

## **Acknowledgments**

Special thanks to the NBA data providers and the open-source Python libraries that made this project possible.

---

## **Contributing**

Feel free to fork the repository and submit pull requests. Suggestions and contributions to improve the project are always welcome.

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

