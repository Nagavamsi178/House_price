"# House_price" 
# 🏠 Housing Price Prediction Pipeline (EC2)

This project contains a complete **Housing Price Prediction (HPP) pipeline** designed to run on an **EC2 / cloud environment** using Python.

---

## 📁 Project Structure

```
hpp_pipeline_ec2/
├── .python-version            # Python version reference
├── app.py                     # Main application file
├── gitlab-runner.exe           # GitLab runner binary
├── housing_price_model.pkl    # Trained ML model
├── india_housing_prices.csv   # Dataset used for training
├── new-key                    # Private SSH key (DO NOT COMMIT PUBLICLY)
├── new-key.pub                # Public SSH key
├── Procfile                   # Process file for deployment
├── README.md                  # Project documentation
├── requirements.txt           # Python dependencies
├── runtime.txt                # Runtime specification
├── set.sh                     # Shell setup script
```

---

## 🚀 Application Purpose

* Train and serve a **housing price prediction model**
* Deployable on **EC2 / cloud servers**
* Supports automation via **GitLab Runner**

---

## 🧠 Model

* Model file: `housing_price_model.pkl`
* Algorithm: Machine Learning regression model
* Dataset: `india_housing_prices.csv`

---

## ▶️ How to Run Locally

```bash
pip install -r requirements.txt
python app.py
```

---

## ☁️ Deployment (EC2 / Cloud)

1. Launch EC2 instance
2. Upload project files
3. Install dependencies
4. Run using:

```bash
python app.py
```

Or use `Procfile` with a process manager.

---

## 🔐 Security Notes

* **Never expose `new-key` (private key)**
* Add sensitive files to `.gitignore`

---

## 📌 Next Improvements

* Add FastAPI / Flask API
* Dockerize the application
* CI/CD with GitLab pipelines
* Model retraining automation

---


