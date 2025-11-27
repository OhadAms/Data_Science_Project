# Data Science Project – Israeli Road Accident Data Extraction and Analysis

## Overview
This project automates the extraction, cleaning, and analysis of Israeli road accident data from the official CBS (Central Bureau of Statistics) website. It uses web automation to download datasets, processes the files using Python data tools, and prepares them for exploration, visualization, and machine-learning workflows.

## Key Features

### 💻 Automated Data Collection
- Utilizes **Selenium WebDriver** and **PyAutoGUI** to control browser actions.
- Navigates the CBS website, selects datasets by year/location/severity, and downloads Excel (`.xlsx`) files.

### 🔍 Data Cleaning & Preparation
- Cleans NaN values, resets indices, and standardizes column names.
- Removes irrelevant rows and converts Excel files to CSV.
- Ensures numerical columns are properly typed for modeling.

### 💾 File Management
- Detects the most recently downloaded dataset.
- Automatically moves files from the system Downloads folder into the project directory.

### 📊 Exploratory Data Analysis (EDA)
- Uses **matplotlib** and **seaborn** for visualizing accident trends.
- Quickly generate histograms and trend analysis.

### 🤖 Machine Learning Ready
- Produces clean datasets suitable for:
  - Regression
  - Classification
  - Any scikit-learn workflow

## Technologies Used

**Python Libraries**
- pandas, numpy, matplotlib, seaborn
- sklearn
- BeautifulSoup
- scipy.stats

**Web Automation**
- selenium
- pyautogui

**System Utilities**
- shutil, glob, os

## How It Works

1. **Browser Automation** – Opens Chrome, navigates CBS website, performs automated selection and file download.
2. **File Handling** – Detects the latest file and moves it to the project path.
3. **Data Cleaning** – Loads and processes the dataset into a clean, structured format.
4. **EDA & ML Prep** – Visualizes data and prepares it for machine-learning pipelines.

## What’s Next?
- Add advanced machine learning pipelines.
- Automate visual and textual reporting (PDF/HTML).
- Integrate cron-based or scheduled data refresh.

## Usage
1. Install Python and all required dependencies.
2. Run the Jupyter Notebook or Python script to collect and process data.
3. Review the generated CSV files and begin further analysis.

---

