# Plant Disease Detection

This project is designed to detect plant diseases using machine learning and image classification techniques. It uses the Plant Village dataset from Kaggle to train a model that can identify diseases based on visual features.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Setup](#setup)
- [Usage](#usage)
- [Model Training](#model-training)
- [License](#license)

## Overview

The Plant Disease Detection project involves:
- Data collection and preprocessing
- Model training and evaluation
- Deployment of the model with a Streamlit web application

## Dataset

The dataset used for this project is the **Plant Village Dataset** from Kaggle. To download the dataset, follow these steps:

1. **Download Kaggle API Key**:
   - Go to your Kaggle account settings and click on "Create New API Token". This will download a `kaggle.json` file containing your Kaggle API credentials.

2. **Set Up Kaggle API**:
   - Place the `kaggle.json` file in the `~/.kaggle/` directory on your machine. If the directory does not exist, create it.

3. **Download Dataset**:
   - Use the Kaggle API to download the dataset by running the following command in your terminal:
     ```sh
     kaggle datasets download -d abdallahalidev/plantvillage-dataset
     ```

   - This command will download the dataset as a zip file. Extract the contents to your project directory.

## Setup

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/noorayym/plant-disease-detection.git
   cd plant-disease-detection

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required Python packages:**

    ```bash
    pip install -r app/requirements.txt
    ```

## Usage

1. **Run the Streamlit application:**

    ```bash
    streamlit run app/main.py
    ```

2. **Open your browser and navigate to `http://localhost:8501` to access the application.**

3. **Enter a tweet in the input box and click 'Classify' to see the classification result.**

## Model Training

The model is trained using the Jupyter Notebook `plants.ipynb`. This notebook includes the following steps:

- Data loading and preprocessing
- Model architecture definition
- Model training
- Evaluation

## License

This project is licensed under the terms of the MIT License.

