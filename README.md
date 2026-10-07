# Laptop Price Predictor 💻

A Machine Learning-powered web application built with **Streamlit** that predicts the price of a laptop based on its configuration.

## Features

Predicts laptop prices using a pre-trained machine learning model (`pipe.pkl`). Users can input the following specifications to get an estimated price:
- **Brand**: Apple, HP, Acer, Asus, Dell, Lenovo, etc.
- **Type**: Ultrabook, Gaming, Netbook, Notebook, etc.
- **RAM (GB)**: 2, 4, 6, 8, 12, 16, 24, 32, 64
- **Weight**: Weight of the laptop in kg
- **Touchscreen**: Yes/No
- **IPS Display**: Yes/No
- **Screen Size**: Screen size in inches
- **Screen Resolution**: High definition resolutions up to 4K
- **CPU**: Intel Core i3, i5, i7, AMD, etc.
- **Storage (HDD & SSD)**: Storage configurations in GB
- **GPU**: Intel, AMD, Nvidia
- **OS**: Windows, Mac, Linux, etc.

## Technologies Used
- **Python**: Core programming language
- **Streamlit**: Web framework for the interactive UI
- **Scikit-Learn**: For building and utilizing the machine learning pipeline
- **Pandas / NumPy**: For data manipulation and numerical operations
- **Pickle**: For serializing and deserializing the machine learning model

## Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/RaunakSachdeva2004/laptop-price-predictor-regression-project.git
   cd laptop-price-predictor-regression-project
   ```

2. **Create a virtual environment (Recommended)**:
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit application**:
   ```bash
   streamlit run app.py
   ```
   The app will open automatically in your default web browser.

## Project Files
- `app.py`: The main Streamlit web application script.
- `laptop-price-predictor.ipynb`: Jupyter notebook containing data exploration, preprocessing, and model training.
- `pipe.pkl`: The serialized scikit-learn pipeline containing the trained regression model.
- `df.pkl`: The serialized pandas DataFrame used to populate dropdown menus in the UI.
- `laptop_data.csv`: The dataset used to train the model.
- `Procfile` & `setup.sh`: Configuration files for deployment (e.g., on Heroku).
