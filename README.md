# *League of Legends Win Rate Prediction*

*This project analyzes **League of Legends** champions and predicts their win rates based on various features such as role, difficulty, attack, defense, and magic power. The goal is to provide players with data-driven recommendations for choosing the best champions based on their preferred role and playstyle.*

## *Table of Contents*
- *[Technologies Used](#technologies-used)*
- *[Dataset](#dataset)*
- *[How to Run](#how-to-run)*
- *[Project Steps](#project-steps)*
- *[Results](#results)*
- *[License](#license)*

## *Technologies Used*
- *Python*
- *Pandas (Data manipulation)*
- *NumPy (Numerical computations)*
- *Scikit-learn (Machine learning models)*
- *Matplotlib & Seaborn (Data visualization)*

## *Dataset*
*The dataset (`lol_champions_current.csv`) is included in this repository. It contains information about 168 League of Legends champions, including features such as:*
- *Popularity*
- *Win Rate*
- *Ban Rate*
- *Attack*
- *Defense*
- *Magic*
- *Difficulty*
- *Role*
- *Tags*

## *How to Run*
1. *Clone this repository:*
   ```bash
   git clone https://github.com/griffinsspike/LoLWR.git

2. Install the required libraries: pip install -r requirements.txt

3. Open the Jupyter Notebook: Open the LolWR.ipynb file in Google Colab or Jupyter Notebook.

4. Run the cells: Execute each cell in the notebook to see the analysis and predictions.

## *Project Steps*
*Data Cleaning and Preprocessing:*

1. Handled missing values and removed irrelevant data.

2. Encoded categorical variables using Label Encoding and One-Hot Encoding.

3.   Normalized numerical features.

*Exploratory Data Analysis (EDA):*

   Visualized the distribution of win rates using histograms.

   Analyzed win rates by role using box plots.

   Explored the relationship between difficulty and win rate using scatter plots.

*3. Machine Learning Models:*

   Linear Regression: Used as a baseline model.

   Random Forest Regressor: Captured non-linear relationships in the data.

   Models were evaluated using R² score and Mean Absolute Error (MAE).

*4. Results and Recommendations:*

   The model successfully predicted win rates and provided recommendations for the top champions in each role (Top, Jungle, Mid, Support, ADC).
   
   Users can input their preferred role and playstyle to receive personalized champion recommendations.
   
   Results
   Achieved an R² score of 0.89 using Random Forest.

Provided user-specific champion recommendations based on role and playstyle.
