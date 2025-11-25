# Diabetesprediction

## **Overview**

This project is a **Diabetes Prediction System** that uses Machine Learning to determine whether an individual is likely to have diabetes based on medical features such as:

* Glucose level
* BMI
* Blood pressure
* Age
* Insulin
* Skin thickness
* Pregnancies
* Family history indicators

The goal is to help with early detection and support healthcare decision-making using data analysis.

---

## **Key Features**

* Predicts diabetes using real-world structured medical data
* Data cleaning, handling missing values, and feature scaling
* Trains multiple ML models (e.g., Logistic Regression, Random Forest, SVM, KNN)
* Shows evaluation metrics (accuracy, confusion matrix, precision, recall)
* User-friendly code for beginners
* Easily extendable with new datasets or additional features
* Can be connected to a web app/GUI for real-time predictions

---

## **Tech Stack**

You can adjust based on what you used:

* **Python**
* **Pandas & NumPy**
* **Scikit-Learn**
* **Matplotlib & Seaborn**
* **Jupyter Notebook / Python scripts**

---

# **How to Open & Run the Project on Your Laptop**

## **1. Download the Project**

* Go to your GitHub repository
* Click the **Code** button
* Select **Download ZIP**

## **2. Unzip the Folder**

* Locate the downloaded ZIP file
* Right-click → **Extract All** (Windows)
* Or just double-click to unzip (Mac)

## **3. Open the Project Folder**

Inside the folder you will see files like:

* `.ipynb` notebook
* `.py` scripts
* Dataset file (usually `.csv`)
* `requirements.txt`

---

# **4. Install Required Libraries**

Open your Terminal (Mac) or CMD (Windows) and run:

```
pip install numpy pandas scikit-learn matplotlib seaborn
```

Or if you have a `requirements.txt`:

```
pip install -r requirements.txt
```

---

# **5. Run the Project**

### **Option A — Jupyter Notebook**

If you're using `.ipynb`:

```
jupyter notebook
```

Then open the notebook and run the cells step by step.

### **Option B — Python Script**

If you're using `.py`:

```
python diabetes_prediction.py
```

(Replace the file name with your actual script.)

---

# **6. View Results**

The project will show:

* Whether the person is **Diabetic** or **Not Diabetic**
* Model accuracy
* Confusion matrix
* Data visualizations
