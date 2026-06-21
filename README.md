# Customer-Segmentation-using-Kmeans
This project focuses on applying unsupervised machine learning to segment mall customers based on their demographic attributes and spending behavior. 
The objective of this project is to segment mall customers into meaningful groups based on their **spending behavior**, **annual income**, and **demographic attributes** using **unsupervised machine learning**.  
By identifying distinct customer clusters, the goal is to help the mall:

- Personalize marketing strategies  
- Improve customer engagement  
- Allocate resources more effectively  
- Understand high‑value vs. low‑engagement customer groups  

This segmentation enables data‑driven decision‑making and targeted marketing campaigns.

---

## 🧠Approach

### 1. Exploratory Data Analysis (EDA)
- Examined distributions of **Age**, **Annual Income**, and **Spending Score**  
- Checked for missing values and outliers  
- Visualized relationships between key features using scatterplots and boxplots  
- Identified natural patterns in spending and income behavior  

### 2. Feature Preparation
- Removed non‑informative features like **CustomerID**  
- Encoded categorical variables (e.g., Gender) if used  
- Scaled numerical features to ensure equal contribution during clustering  

### 3. K-Means Clustering
- Used the **Elbow Method** to determine the optimal number of clusters  
- Trained the K-Means model on selected features  
- Assigned each customer to a cluster  
- Profiled each cluster using summary statistics  

### 4. Cluster Visualization
- Applied **PCA** or **t‑SNE** for dimensionality reduction  
- Created 2D scatter plots to visually confirm cluster separation  
- Used color‑coded clusters to interpret customer groups clearly  

### 5. Insight Generation
- Analyzed each cluster’s characteristics  
- Proposed marketing strategies tailored to each segment  

---

## 📊 Results and Findings

The clustering analysis revealed **clear and meaningful customer segments**, each with distinct behavioral patterns. A typical segmentation outcome includes groups such as:

### **1. High Income – High Spending**
- Premium, loyal customers  
- Respond well to exclusivity and personalized services  
- **Strategy:** VIP programs, luxury promotions, early access events  

### **2. High Income – Low Spending**
- Wealthy but less engaged  
- Potential to increase spending with targeted incentives  
- **Strategy:** Personalized outreach, curated product bundles  

### **3. Moderate Income – Moderate Spending**
- Stable, regular shoppers  
- Represent the mall’s core customer base  
- **Strategy:** Loyalty rewards, seasonal offers  

### **4. Low Income – High Spending**
- Highly engaged despite lower income  
- Value‑driven but enthusiastic  
- **Strategy:** Discounts, bundle deals, value‑focused messaging  

### **5. Low Income – Low Spending**
- Least engaged segment  
- May require awareness and trust‑building  
- **Strategy:** Entry‑level offers, budget‑friendly campaigns  

---

## ✅ Final Insight

The analysis shows that **spending behavior cannot be predicted by income alone**.  
Behavioral metrics like **Spending Score** play a crucial role in understanding customer engagement.  
The clusters were well‑separated in PCA/t‑SNE visualizations, confirming that K-Means successfully captured meaningful structure in the data.

This segmentation provides a strong foundation for **targeted marketing**, **customer retention**, and **strategic decision‑making**.

