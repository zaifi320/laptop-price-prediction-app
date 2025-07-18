# 💻 Laptop Price Prediction with GUI (Jupyter Notebook Version)

This project is a **Machine Learning-based Laptop Price Predictor** that uses a trained regression model to estimate laptop prices based on specifications such as brand, CPU, RAM, GPU, etc. The model is integrated with a **Tkinter GUI**, and the entire system runs within a **Jupyter Notebook**.

---

## 📌 Features

* 🔍 Predict laptop price based on user inputs
* 📊 Cleaned and processed dataset with feature engineering
* 🧠 Built with `Linear Regression` using `scikit-learn`
* 🧱 Uses `OneHotEncoder` for categorical features
* 🖥️ GUI built using `Tkinter` inside the notebook
* 📁 Includes data preprocessing, model training, evaluation, and prediction

---

## 🛠 Technologies Used

* Python
* Jupyter Notebook
* pandas, NumPy
* scikit-learn
* Tkinter
* matplotlib (optional, for visualization)

---

## 📁 Project Structure

```
Laptop Prediction.ipynb   # Main notebook with full code (preprocessing + training + GUI)
saved_data.csv           # Laptop dataset used for training
requirements.txt          # List of required Python packages
README.md                 # This file
```

---

## 🧠 Model Overview

* **Target Variable:** Laptop price (log-transformed)

* **Features Used:**

  * Brand
  * CPU
  * RAM type and size
  * Storage (HDD, SSD)
  * GPU Brand
  * Operating System
  * Generation
  * Number of Cores
  * PPI (Pixels Per Inch)

* **Preprocessing Steps:**

  * One-hot encoding for categorical columns
  * Feature scaling (if needed)
  * Model trained using `LinearRegression` from `sklearn`

---

## 🧪 How to Use

1. 📥 Clone or download this repository.

2. 🔧 Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. ▶️ Open the `Laptop Prediction.ipynb` in Jupyter Notebook.

4. 🔢 Run all cells one by one.

5. 🖱️ A Tkinter GUI window will pop up.

6. 👨‍💻 Fill in laptop specs and click **Predict Price** to get an estimated price.

---

## 📷 Screenshot

<img src="[https://user-images.githubusercontent.com/your_image.png](https://github.com/zaifi320/laptop-price-prediction-app/blob/2256a573222229f60c754672df4e5b7c8d46834c/GUI_Sample.png)" width="600"/>

---

## 📌 Note

* The GUI is embedded **within the notebook**. No `.py` file is needed to launch it.
* If you want to convert it into a `.py` script later, we can help refactor it.

---

## ⚠️ Disclaimer

This project is for **educational purposes only**. The price predictions are based on historical data and a simplified model and should not be used for real-world financial decisions.

---

## 🗣️ Feedback

If you find any bugs, have suggestions, or want to improve the GUI or model, feel free to open an issue or pull request. ⭐ the repo if you found it helpful!

---

## 👤 Author
Huzaifa Saeed
📧 huzaifasaeed661@gmail.com
🔗 www.linkedin.com/in/huzaifabinsaeed
