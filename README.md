🛠️ My Approach

Performed careful missing value analysis, distinguishing between true missing data and absence-based features (e.g., Alley, PoolQC, Fence).

Filled absence-based categorical features explicitly with "None" to preserve semantic meaning.

Applied median imputation for numerical features and most-frequent strategy for remaining categorical features.

Converted categorical variables to category dtype and encoded them using OneHotEncoder with handle_unknown="ignore".

Built a clean preprocessing pipeline using ColumnTransformer.

Trained and compared multiple regression models:

RandomForestRegressor

ExtraTreesRegressor

HistGradientBoostingRegressor

Tuned hyperparameters using GridSearchCV and selected the best model based on cross-validated RMSE.

Generated predictions on the test set and created a valid Kaggle submission.

🏆 Kaggle Achievement

Public Leaderboard Score: 0.14444

Result: First successful Kaggle submission

Status: Ranked on the leaderboard ✅
