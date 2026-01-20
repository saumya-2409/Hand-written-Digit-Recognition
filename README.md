# Digit Recognizer (MNIST) with Random Forest

A Machine Learning model to recognize handwritten digits (0-9) using the MNIST dataset. This project was developed as part of a Digit Recognition assignment.

## 🚀 How It Works
This notebook uses the `opendatasets` library to automatically download the training and test data from Kaggle. You do not need to manually download CSV files.

* **Model:** Random Forest Classifier
* **Libraries:** Pandas, Scikit-Learn, Opendatasets
* **Accuracy:** ~96%

## 🛠️ Usage
1.  **Clone or Download** this repository.
2.  **Run the Notebook:**
    ```bash
    jupyter notebook code.ipynb
    ```
3.  **Kaggle Credentials:** When you run the first few cells, the notebook will ask for your Kaggle username and key (API Token) to download the dataset. 
    * *To get your key: Go to Kaggle Settings -> Create New Token.*

## 📂 Dataset
The dataset is sourced from the [Digit Recognizer Competition](https://www.kaggle.com/competitions/digit-recognizer/data). 
* **Note:** The code handles the download automatically.
