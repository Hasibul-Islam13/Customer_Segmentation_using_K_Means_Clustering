# Customer_Segmentation_using_K_Means_Clustering

**Course Instructor**: Md. Mynoddin, Assistant Professor, Department of CSE, RMSTU 

---

## 📌 Overview  
This project segments mall customers into distinct groups based on their **Annual Income** and **Spending Score** using **K-Means Clustering**. The goal is to enable businesses to tailor marketing strategies to specific customer profiles.  

---

## 🛠️ Tools & Technologies  
- **Programming Language**: Python  
- **Libraries**: Pandas, Scikit-learn, Matplotlib, Seaborn  
- **Platform**: Google Colab  

---

## 📂 Dataset  
- **Source**: [Kaggle - Mall Customers Dataset]
- **Features**:  
  - CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100)  

---

## 🚀 Steps  
1. **Data Preprocessing**: Check for null values and select relevant features.  
2. **Elbow Method**: Determine optimal clusters (k=5).  
3. **K-Means Clustering**: Group customers into 5 segments.  
4. **Visualization**: Scatter plot of clusters with centroids.  
5. **Interpretation**: Label clusters (e.g., "High Income, Low Spenders").  

---

## 📊 Results  
- **Optimal Clusters**: 5 (validated via the Elbow Method).  
- **Cluster Visualization**:  
  <p align="center">  
    <img src="clusters.png" alt="Cluster Visualization" width="500">  
  </p>  

---

## ⚠️ Limitations  
- No feature scaling applied.  
- Assumes spherical clusters (K-Means limitation).  

---

## 🔮 Future Work  
- Integrate **Age** and **Gender** for multi-dimensional analysis.  
- Compare with **DBSCAN** or **Hierarchical Clustering**.  

---

## 🙏 Acknowledgements  
This project was guided by **Md. Mynoddin**, Assistant Professor, Department of CSE, RMSTU. His insights on machine learning methodologies were invaluable to this work.  

---
