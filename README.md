
# Lead Scoring Analysis

## Overview

This project aims to analyze and score leads to enhance lead quality and increase conversion rates. The analysis is based on a dataset containing various attributes of leads, and a lead scoring model is developed to predict the likelihood of lead conversion.

## Dataset

The dataset `Leads.csv` contains 9240 records with the following key attributes:
- `Prospect ID`
- `Lead Number`
- `Lead Origin`
- `Lead Source`
- `Do Not Email`
- `Do Not Call`
- `Converted`
- `Total Visits`
- `Total Time Spent on Website`
- `Page Views Per Visit`
- And other relevant features

## Preprocessing

Data preprocessing involves:
1. Handling missing values.
2. Normalizing or transforming data.
3. Feature engineering to create new features from existing ones.

## Model

The lead scoring model uses machine learning algorithms to predict the conversion of leads. The following steps are included in the model development:
1. **Data Splitting:** The dataset is split into training and testing sets.
2. **Model Training:** Different algorithms such as Logistic Regression, Decision Trees, etc., are trained on the training set.
3. **Evaluation:** The models are evaluated using performance metrics such as accuracy, precision, recall, and F1-score.

## Results

The performance of the models is evaluated, and the best model is selected based on the evaluation metrics. The results are interpreted to understand the key factors influencing lead conversion.

## Visualizations

The following visualizations are created to illustrate the analysis:
1. **Pie Chart:** Distribution of leads converted vs. not converted.
2. **Pairplot 1:** Relationships between Total Visits, Total Time Spent on Website, and Page Views Per Visit with conversion status.
3. **Pairplot 2:** Detailed analysis of relationships between key variables and conversion status.

## Usage

To run the analysis and generate the lead scoring model, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/lead-scoring-analysis.git
   cd lead-scoring-analysis
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   Open `Lead Scoring.ipynb` in Jupyter Notebook and execute the cells to perform the analysis and model training.

4. **View Visualizations:**
   The visualizations are generated within the Jupyter Notebook. Ensure to run the cells to see the visual representations of the analysis.

## Conclusion

This project demonstrates a comprehensive approach to lead scoring using data analysis and machine learning techniques. The insights derived from the analysis can help businesses focus on the most promising leads and improve their marketing strategies.
