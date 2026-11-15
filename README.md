# Customer Purchase Behavioural Analysis And Aegis Station - OutBreak Analysis

## Project Team

| Name | Roll Number |
|---|---|
| CH. L Karthik | EC24B1108 |
| O. Sai | EC24B1109 |
| S. Yagnesh | EC24B1103 |

## Project Parts

This project consists of two parts:

| Part | Project Title | Description | Link |
|---|---|---|---|
| Part A | Customer Purchase Behavioural Analysis | Analysis of customer purchasing patterns and prediction of repeat purchases using machine learning. | This repository |
| Part B | Aegis Station – OUTBREAK ANALYST | A browser-based data-science strategy game involving outbreak analysis and decision-making through interactive missions. | [Play Game](https://aegis-station-0db463.netlify.app) · [HTML File](./outbreak_analyst.html) |

---

# Part A: Customer Purchase Behavioural Analysis

## 1. Project Overview

This project analyses customer purchasing behaviour using the UCI Online Retail dataset. It explores purchasing patterns, customer activity, and repeat purchase behaviour. Machine learning models are developed to predict whether a customer will make another purchase.

## 2. Objectives

- Analyse customer purchasing patterns.
- Perform data cleaning and preprocessing.
- Explore sales trends and customer behaviour.
- Engineer features for repeat purchase prediction.
- Build and evaluate machine learning models.
- Compare model performance using evaluation metrics.

## 3. Dataset Description

The project uses the **Online Retail Dataset** from the UCI Machine Learning Repository.

**Dataset:** Online Retail

**Source:** [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

The dataset contains transactional records from a UK-based online retail business.

## 4. Project Structure

```text
Customer-Purchase-Behavioural-Analysis/
│
├── Online Retail.xlsx
├── outbreak_analyst.html
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01_Data_Preparation.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   ├── 04_Baseline_Model.ipynb
│   ├── 05_Logistic_Regression.ipynb
│   ├── 06_Random_Forest.ipynb
│   └── 07_Model_Comparison_Prediction.ipynb
│
├── processed_data/
│   ├── cleaned_online_retail.csv
│   ├── X_train.csv
│   ├── X_test.csv
│   ├── y_train.csv
│   └── y_test.csv
│
├── models/
│   ├── logistic_regression.pkl
│   └── random_forest.pkl
│
└── results/
    ├── monthly_revenue.png
    ├── country_revenue.png
    ├── logistic_confusion_matrix.png
    ├── random_forest_confusion_matrix.png
    ├── model_comparison.png
    └── feature_importance.png
```

*The folder structure above shows the intended organisation. Include only files that are actually present in your repository.*

## 5. Notebook Descriptions

| Notebook | Description |
|---|---|
| 01_Data_Preparation | Loads the original dataset and performs data cleaning and preprocessing. |
| 02_EDA | Explores customer purchasing patterns and sales trends. |
| 03_Feature_Engineering | Creates features and prepares training and testing datasets. |
| 04_Baseline_Model | Establishes a baseline using a Dummy Classifier. |
| 05_Logistic_Regression | Trains and evaluates the Logistic Regression model. |
| 06_Random_Forest | Trains and evaluates the Random Forest model. |
| 07_Model_Comparison_Prediction | Compares model performance and performs customer-level predictions. |

## 6. Machine Learning Workflow

1. Data collection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Feature engineering
5. Train-test splitting
6. Baseline model development
7. Logistic Regression model development
8. Random Forest model development
9. Model evaluation and comparison
10. Repeat purchase prediction

## 7. Target Variable

The target variable represents repeat purchase behaviour:

- **1:** The customer made another purchase during the observed future period.
- **0:** No further purchase was observed during the defined period.

This target represents repeat purchasing, not product returns or refunds.

## 8. Results and Visualisations

The project includes visualisations and evaluation results such as:

- Monthly revenue analysis
- Country-wise revenue analysis
- Logistic Regression confusion matrix
- Random Forest confusion matrix
- Model performance comparison
- Feature importance analysis

## 9. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Scikit-learn | Machine learning |
| Joblib | Model saving and loading |
| Jupyter Notebook | Development environment |

## 10. Installation and Setup

### Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
cd YOUR-REPOSITORY-NAME
```

### Create a virtual environment (optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Activate it on Linux or macOS:

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

Alternatively, install the packages individually:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install openpyxl
pip install joblib
pip install jupyter
```

### Verify installation

```bash
python -c "import pandas, numpy, matplotlib, seaborn, sklearn, joblib, openpyxl; print('All packages installed successfully!')"
```

## 11. Execution Order

Run the notebooks in the following order:

1. `01_Data_Preparation.ipynb`
2. `02_EDA.ipynb`
3. `03_Feature_Engineering.ipynb`
4. `04_Baseline_Model.ipynb`
5. `05_Logistic_Regression.ipynb`
6. `06_Random_Forest.ipynb`
7. `07_Model_Comparison_Prediction.ipynb`

The notebooks save processed datasets, trained models, and result files into their respective folders.

---

# Part B: Aegis Station – OUTBREAK ANALYST

## 1. Game Overview

**OUTBREAK ANALYST** is a browser-based, single-file data-science strategy game. You are the Chief Scientific Officer aboard Aegis Station, where an unknown pathogen is spreading.

Analyse the evidence, work through the data-science missions, and make decisions to contain the outbreak.

<ins>Play the game:</ins> [Aegis Station – OUTBREAK ANALYST](https://aegis-station-0db463.netlify.app)

## 2. Game Details

| Feature | Description |
|---|---|
| Title | OUTBREAK ANALYST |
| Setting | Aegis Station, a fictional orbital research station |
| Format | Standalone HTML5 game |
| Missions | 10 data-science and outbreak-response missions |
| Dependencies | No separate libraries or installation required |
| Audio | Browser-generated sound effects with a mute/unmute control |

## 3. Game File

The complete game is provided as a standalone HTML file in the root directory of this repository.

**File:** [outbreak_analyst.html](./outbreak_analyst.html)

The HTML file contains the game's interface, styling, animation, and JavaScript logic. No separate game folder or README file is required.

## 4. How to Play Locally

1. Download `outbreak_analyst.html` from this repository.
2. Double-click the file to open it in a modern browser such as Google Chrome, Microsoft Edge, or Firefox.
3. Select **Accept Transmission** on the opening screen.
4. Follow the mission instructions and on-screen prompts.
5. Complete the missions and make decisions to contain the outbreak.
6. Use the speaker control in the top-right area to mute or unmute the sound.

An internet connection is not normally required to play the standalone HTML file.

## 5. Play Online

The game is also hosted online and can be accessed through the following link:

**[Play Aegis Station – OUTBREAK ANALYST](https://aegis-station-0db463.netlify.app)**

Open the link in a modern web browser to start playing.

## 6. Publishing the Game with OneClick Live

To host the game using OneClick Live:

1. Open the OneClick Live website or app and sign in if required.
2. Choose the option to create, upload, or deploy a web project.
3. Upload `outbreak_analyst.html`.
4. If the platform requires the website entry file to be named `index.html`, rename a copy of the game file to `index.html`. Do not change its contents.
5. Start the deployment or publishing process.
6. Wait for the platform to provide the hosted website URL.
7. Open the URL in a private/incognito browser window and test it on another device if possible.
8. Share the hosted URL to allow others to access the game.

**Note:** Uploading the HTML file to GitHub does not automatically publish it as a playable website. The hosted game URL is provided by the deployment platform.

## 7. Updating the Published Game

When making changes to the game:

1. Keep a backup of the current working HTML file.
2. Edit and test the updated file locally.
3. Upload the updated HTML file to the same hosting project.
4. Use the platform's redeploy, update, or publish option.
5. Reopen the public URL and confirm that the latest version is displayed.
6. If an older version appears, try a hard refresh or private/incognito window.

## 8. Troubleshooting

| Issue | What to Try |
|---|---|
| The game does not open | Download the HTML file again and open it using an updated Chrome, Edge, or Firefox browser. |
| The hosted page is blank or shows a 404 | Check that the uploaded file is the website entry file. If required, name it `index.html` and redeploy. |
| The game works locally but not after publishing | Confirm that the complete original HTML file was uploaded and deployment finished successfully. |
| Sound is not audible | Check device and browser volume and ensure the game's speaker control is not muted. |
| Changes are not visible | Redeploy the latest file, then hard-refresh the hosted page or test in a private window. |
| The game layout looks unusual on a device | Try a current desktop browser first, then test the hosted page on the target device. |

---

## 12. Future Improvements

- Explore additional customer behaviour patterns.
- Experiment with more machine learning algorithms.
- Improve repeat purchase prediction.
- Extend the interactive game with additional missions and scenarios.

## 13. License and Usage

This project is developed for academic and educational purposes.

The Online Retail dataset is sourced from the UCI Machine Learning Repository. Refer to the dataset's official page for its usage terms.

The Aegis Station game is provided as a standalone HTML5 file for browser-based gameplay.
