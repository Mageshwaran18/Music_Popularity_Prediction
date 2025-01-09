# 🎵 Music Popularity Prediction

Predict the popularity of songs using machine learning techniques based on audio features and metadata. This project leverages data from Spotify's API to build and evaluate predictive models.

## 🚀 Features

- **Data Cleaning**: Handles missing values and performs essential preprocessing.
- **Visualization**: Uses Seaborn and Matplotlib for insightful data analysis.
- **Feature Engineering**: Encodes categorical data and prepares features for modeling.
- **Machine Learning**: Implements an XGBoost Regressor for popularity prediction.
- **Model Evaluation**: Uses metrics like MSE, MAE, and R² to assess model performance.

## 🛠️ Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - Pandas, NumPy: Data manipulation
  - Seaborn, Matplotlib: Data visualization
  - Scikit-learn: Preprocessing and metrics
  - XGBoost: Machine learning model

## 📂 Workflow

1. **Data Loading**: Import data from `SpotifySongPopularityAPIExtract.csv`.
2. **Exploratory Data Analysis**:
   - Check for missing values.
   - Perform descriptive analysis and sampling.
3. **Preprocessing**:
   - Remove rows with missing values.
   - Encode categorical columns.
4. **Modeling**:
   - Split the data into training and testing sets.
   - Train an XGBoost Regressor.
5. **Evaluation**:
   - Calculate performance metrics (MSE, MAE, R², etc.).

## 📊 Dataset

The dataset used in this project includes:

- **Audio Features**: Danceability, Energy, Tempo, Loudness, etc.
- **Metadata**: Song name, Artist, Album, and Popularity score.

> Dataset: `SpotifySongPopularityAPIExtract.csv` (Ensure it is available in the working directory.)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mageshwaran18/Music_Popularity_Prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🧑‍💻 Usage

1. **Run the notebook**:
   - Open `Music_Popularity_Prediction.ipynb` in Jupyter Notebook or any compatible IDE.
   - Execute cells step by step to reproduce the analysis and modeling.

2. **Evaluate the model**:
   - Adjust hyperparameters and observe the impact on metrics.

## 📈 Results

The XGBoost model achieved the following:

- **Mean Absolute Error (MAE)**: 5.071
- **R² Score**: 0.8916

> Replace X, Y, and Z with the actual results after running the notebook.

## 🤝 Contribution

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss your ideas.

---

Feel free to explore, experiment, and enhance the prediction model. Happy coding! 😄

