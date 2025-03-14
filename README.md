<h1 align="center" style="color:#4CAF50;">📱 Mobile Price Prediction using Machine Learning 🚀</h1>

![Mobile Market](https://upload.wikimedia.org/wikipedia/commons/3/34/Smartphone_icon.png)

---

## 🔍 **Project Overview**
The **mobile phone market** is highly competitive, with prices influenced by **RAM, battery life, screen size, and brand reputation**. This project builds a **Machine Learning model** to **predict smartphone prices** based on key specifications.  

> 📌 **Key Features**  
✅ Predicts mobile phone prices based on RAM, Battery, and Screen Size  
✅ Uses **Linear Regression** for prediction  
✅ Includes **Feature Engineering** (Performance Score, Battery Efficiency)  
✅ **Beautiful Visualizations** for price insights  

---

## 📊 **Dataset Overview**
This dataset consists of **930 smartphone models** with **15 key attributes**, including:

✔ **Brand & Model Name** – Identify leading smartphone brands  
✔ **RAM & Processor** – Key performance metrics ⚡  
✔ **Camera Specifications** – Front & back camera details 📸  
✔ **Battery Capacity** – Power backup insights 🔋  
✔ **Screen Size** – Display dimensions impacting usability 📺  
✔ **Launched Prices** – Pricing across **multiple countries** 🌍  

📌 **Example Data:**
```plaintext
| Brand   | Model        | RAM  | Battery Capacity | Screen Size | Price (INR) |
|---------|-------------|------|-----------------|-------------|-------------|
| Apple   | iPhone 13   | 6GB  | 3200mAh         | 6.1 inches  | 79,990      |
| Samsung | Galaxy S22  | 8GB  | 3700mAh         | 6.7 inches  | 72,999      |
| Xiaomi  | Redmi Note  | 6GB  | 5000mAh         | 6.6 inches  | 16,499      |


#🏗️ Project Workflow
graph TD;
  A[Load & Clean Data] --> B[Feature Engineering];
  B --> C[Train Linear Regression Model];
  C --> D[Evaluate Model Performance];
  D --> E[Make Predictions & Visualize];
  E --> F[Generate Business Insights];

📢 Key Insights & Business Recommendations
✅ Higher RAM and battery capacity lead to higher prices
✅ Budget smartphones (≤6GB RAM, ≤4000mAh battery) are priced under ₹20,000
✅ Flagship models (≥8GB RAM, 4500mAh+ battery) are priced over ₹50,000
✅ Retailers can use this model to set competitive pricing for new models

📌 Next Steps: 🔥 Try Random Forest Regression for better accuracy
🔥 Include Processor Type & Storage for deeper analysis
🔥 Deploy the model using Flask or FastAPI

