## 💻 Laptop Price Predictor

This is a machine learning project that predicts the price of a laptop based on its specifications such as brand, processor type, RAM size, storage, GPU brand, and more. The project includes a user-friendly **Tkinter GUI** for easy price prediction without using code.

---

### 📸 GUI Preview

<img src="screenshot.png" width="600"/>

---

## 🚀 Features

* One-click laptop price prediction
* Built with `scikit-learn` and `Tkinter`
* Uses OneHotEncoding and Linear Regression
* Supports categorical and numerical features
* Real-time input and instant prediction
* Clean, interactive graphical interface

---

## 🧠 Model Details

* **Model Type:** Linear Regression
* **Preprocessing:** OneHotEncoder for categorical features
* **Log Transformation:** Target variable (Price) is log-transformed for better accuracy
* **Pipeline:** Sklearn pipeline for combining preprocessing and model

---

## 🛠️ Technologies Used

* Python 3
* Pandas
* Numpy
* Scikit-learn
* Tkinter (GUI)
* Seaborn / Matplotlib (Data Analysis)
* Joblib (Model saving)

---

## 🗂️ Project Structure

```
Laptop-Price-Predictor/
│
├── Laptop Prediction.ipynb      # Jupyter Notebook for data analysis & model training
├── app.py                       # Main file to run GUI application
├── model.pkl                    # Trained model pipeline (joblib file)
├── requirements.txt             # All dependencies
├── README.md                    # Project documentation
└── screenshot.png               # Image of the GUI (optional)
```

---

## ⚙️ Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/Laptop-Price-Predictor.git
   cd Laptop-Price-Predictor
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**

   ```bash
   python app.py
   ```

---

## 📋 How to Use

1. Open the GUI by running `app.py`
2. Fill in laptop specs like Brand, Core, RAM, etc.
3. Click **Predict** and get the estimated price instantly

---

## 📁 Dataset

* The dataset was cleaned and preprocessed in the Jupyter Notebook.
* Features include:

  * Brand
  * CPU type
  * RAM type
  * Generation
  * Core
  * RAM size
  * Storage (HDD/SSD)
  * GPU Brand
  * Operating System
  * PPI (Pixels per inch)

---

## 📌 Output

* The model predicts **log price**, which is converted back to the **actual price** using exponentiation.
* Prediction is shown directly in the GUI.

---

## ⚠️ Disclaimer

This model provides **approximate price predictions** based on historical data. It may not reflect the exact market price of new or used laptops.

---

## 💬 Feedback

Have suggestions or found a bug? Feel free to open an issue or submit a pull request!

---

Let me know if you want:

* Urdu version
* A logo/banner
* Deployment guide (e.g., using PyInstaller or Streamlit)
