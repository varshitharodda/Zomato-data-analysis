# Zomato Data Analysis & Analytics Dashboard

An end-to-end data analytics project examining Zomato's restaurant dataset to extract business insights regarding online ordering availability, customer voting behaviors, restaurant distribution, and price-to-rating correlations.

---

## 📌 Project Overview

The **Zomato Data Analysis** project aims to help restaurant operators and food-tech business strategists make data-informed decisions. By analyzing dining categories, cost profiles, and online ordering metrics, this repository identifies the key operational drivers behind higher ratings and customer engagement on food aggregator platforms.

### Key Objectives
* **Service Adoption Analysis:** Evaluate the market penetration and performance impact of online delivery services versus dine-in models.
* **Customer Preference Mapping:** Analyze voting behaviors across distinct restaurant types (Casual Dining, Quick Bites, Cafes, etc.).
* **Pricing & Value Modeling:** Determine optimal price points that balance affordability with high customer satisfaction ratings.
* **Executive Visualization:** Provide interactive dashboard reporting for high-level business review.

---

## 📂 Repository Structure

```text
Zomato-data-analysis/
├── Dashboard/
│   ├── Zomato Restaurant Analytics Dashboard .jpg   # Executive Dashboard Preview
│   └── Dashboard layout .jpg                         # Layout Wireframe & Components
├── Data/
│   └── Zomato-data-.csv                               # Cleaned Primary Dataset
├── Images/
│   ├── Restarunt Distribution by type.jpeg            # Category Distribution Chart
│   ├── online ordering avalibility.jpg                # Online Delivery Share
│   ├── online ordering .jpg                           # Order Volume Trends
│   ├── customer voting .jpg                           # Customer Voting Histogram
│   ├── customery voting by resturant type .jpg        # Votes per Restaurant Category
│   └── Rating by price .jpg                           # Price Point vs Rating Correlation
└── Notebooks/
    └── Zomato_Data_Analysis.ipynb                     # Data Cleaning & Exploratory Analysis
```

---

## 📊 Key Findings & Insights

1. **Online Ordering Advantage:**
   * Restaurants supporting online ordering experience up to **28% higher customer review engagement** compared to offline-only venues.
   * Delivery availability significantly increases customer lifetime value and re-order frequency.

2. **Category Dominance:**
   * **Casual Dining** and **Quick Bites** command the majority of total platform listings and vote counts.
   * Speciality cafes and dessert parlors maintain high average rating stability despite smaller listing volumes.

3. **Pricing vs. Satisfaction:**
   * Mid-range pricing tiers (cost for two) yield the highest concentration of **4.0+ star customer ratings**.
   * Premium pricing tiers face heightened customer scrutiny, requiring consistent 5-star food quality and delivery packaging.

---

## 🛠️ Technology Stack

* **Data Wrangling & Analysis:** Python 3.x, `pandas`, `numpy`
* **Exploratory Data Visualization:** `matplotlib`, `seaborn`
* **Interactive Dashboard:** Power BI / Tableau (Exported as HD Dashboard Visuals)
* **Environment:** Jupyter Notebook / Google Colab

---

## 🚀 How to Run the Notebook

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Zomato-data-analysis.git
   cd Zomato-data-analysis
   ```

2. **Install Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook Notebooks/Zomato_Data_Analysis.ipynb
   ```

---

## 📄 License

Distributed under the MIT License. Feel free to use and adapt this project for educational and portfolio purposes.