# Protecting Montpelier: Strategies for Flood Risk Mitigation

A Business Analytics Capstone Project by Drexel LeBow – Fall 2024  
Team: Ankit Akash, Arjun Malgwa, Sidhant Kumar, Ashikul Kabir, Shraddha Jain, Sana Parab

---

## 📌 Overview

Montpelier, Vermont has experienced increased flood risks, especially in 2023–2024. Our project addresses how insurance companies can better assess property flood risk and underinsurance using enriched property-level data and clustering-based analytics.

- Clean and validate address data
- Geocode locations using Precisely APIs
- Query flood risk information
- Identify vulnerable or underinsured properties

---

## 🧰 Tools & Technologies
- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **K-means Clustering**
- **Principal Component Analysis (PCA)**
- **Precisely APIs** – for Geoaddressing and Floodrisk data
- **MapInfo Pro**, **Tableau** – for geospatial and visual analysis

---

## 🔐 Environment Setup

Create a `.env` file in the root directory:

```bash
AUTH_TOKEN=your_precisely_api_token
```
---

## 💡 Key Contributions

### ✅ Clustering-Based Flood Risk Assessment
- Segmented 4,184 properties into 5 clusters using flood zone, elevation, and proximity to Winooski River.
- Identified high-risk properties for insurers to prioritize.

### ✅ Underinsurance Detection
- Analyzed Insurance-to-Value (ITV) ratio using policy vs. market value.
- Identified underinsured properties with an average coverage gap of $147,689.

### ✅ Business Insights
- Recommended custom flood insurance bundles and upselling strategies based on risk clusters.

---

## 🔐 Security Note
Any API keys or tokens have been removed for public safety. Use `.env` files or OS environment variables to store credentials when reproducing results.

---

## 📊 Visualizations
Tableau dashboards and K-means cluster visualizations highlight:
- High-risk vs low-risk property zones
- Cluster-level insurance strategy recommendations

---

## 📍 Location
Montpelier, Vermont (ZIP prefix: `056`)  
Focus on flood risk along the **Winooski River corridor**

---

## 📬 Contact
**Ankit Akash**  
[LinkedIn](https://www.linkedin.com/in/ankit-akash) | [GitHub](https://github.com/AnkitAkash)

---

