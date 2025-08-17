WatchPrice – Predict Smartwatch Prices with Machine Learning

Overview
WatchPrice is a machine learning project that predicts the price of smartwatches based on their features (like brand, model, battery life, ratings, display size, etc.).
The project includes notebooks for data cleaning, feature engineering, model building, and a main pipeline that lets you test predictions.

Features
- Collects and prepares smartwatch data
- Cleans and transforms raw data into useful features
- Trains multiple ML models to predict price
- Lets you test predictions with new watch inputs
- Easy to extend with new data or algorithms

Project Structure
WatchPrice/
│
├── data/                       -> Dataset files
├── src/                        -> Source code / helper scripts
├── feature_engineering.ipynb   -> Notebook for data cleaning & preprocessing
├── build_models.ipynb          -> Notebook for training ML models
├── main.ipynb                  -> Notebook for running the pipeline & testing predictions
├── requirements.txt            -> Python dependencies
└── README.txt                  -> Project documentation

How to Run
1. Clone the Repository
   git clone https://github.com/AIStudiosML/WatchPrice.git
   cd WatchPrice

2. Install Dependencies
   pip install -r requirements.txt

3. Open Jupyter Notebook
   jupyter notebook

4. Run the Notebooks in Order
   - feature_engineering.ipynb: Clean and transform the dataset
   - build_models.ipynb: Train machine learning models
   - main.ipynb: Test predictions with new inputs

Example Use Case
If you enter details of a smartwatch like:
- Brand: Samsung
- Display Size: 1.5 inch
- Battery Life: 7 days
- Strap Material: Silicon
- Ratings: 4.5

The model will try to predict its market price.

Requirements
This project uses popular Python libraries such as:
- pandas – data handling
- numpy – numerical operations
- scikit-learn – machine learning models
- matplotlib / seaborn – visualization

(See requirements.txt for the full list.)

Future Improvements
- Add deep learning models for better accuracy
- Build a web app interface for easier predictions
- Include real-time smartwatch data scraping