<h2>🛠️ My Approach</h2>

<ul>
  <li>Performed careful missing value analysis, distinguishing between true missing data and absence-based features (e.g., Alley, PoolQC, Fence).</li>

  <li>Filled absence-based categorical features explicitly with <code>"None"</code> to preserve semantic meaning.</li>

  <li>Applied median imputation for numerical features and most-frequent strategy for remaining categorical features.</li>

  <li>Converted categorical variables to category dtype and encoded them using OneHotEncoder with <code>handle_unknown="ignore"</code>.</li>

  <li>Built a clean preprocessing pipeline using ColumnTransformer.</li>

  <li>Trained and compared multiple regression models:
    <ul>
      <li>RandomForestRegressor</li>
      <li>ExtraTreesRegressor</li>
      <li>HistGradientBoostingRegressor</li>
    </ul>
  </li>

  <li>Tuned hyperparameters using GridSearchCV and selected the best model based on cross-validated RMSE.</li>

  <li>Generated predictions on the test set and created a valid Kaggle submission.</li>
</ul>

<h2>🏆 Kaggle Achievement</h2>

<p>
  <img src="images/leaderboard.png" alt="Kaggle Leaderboard Result" />
</p>

<ul>
  <li><strong>Public Leaderboard Score:</strong> 0.14444</li>
  <li><strong>Result:</strong> First successful Kaggle submission</li>
  <li><strong>Status:</strong> Ranked on the leaderboard ✅</li>
</ul>
