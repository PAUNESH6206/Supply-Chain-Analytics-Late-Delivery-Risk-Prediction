# **Supply Chain Analytics: Late Delivery Risk Prediction**

This project focuses on analyzing supply chain data to predict late delivery risks and derive actionable insights for improving delivery performance. The dataset includes information on orders, shipping, sales, and customer details. The analysis is performed using Python for data cleaning, exploratory data analysis (EDA), and predictive modeling, and the results are visualized in a Power BI dashboard.

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Workflow](#workflow)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

---

## **Project Overview**
The goal of this project is to:
- Analyze delivery performance and identify factors contributing to late deliveries.
- Predict the risk of late deliveries using machine learning models.
- Visualize key insights in an interactive Power BI dashboard.

---

## **Dataset**
The dataset contains **53 columns** related to orders, customers, products, and logistics. Key columns include:
- **Delivery Metrics**: `Days for shipping (real)`, `Days for shipment (scheduled)`, `Late_delivery_risk`.
- **Sales & Profitability**: `Sales per customer`, `Benefit per order`, `Order Profit Per Order`.
- **Customer Details**: `Customer Segment`, `Customer Country`.
- **Product Details**: `Product Category Name`, `Product Price`.

The dataset is available on [Kaggle](https://www.kaggle.com/datasets/your-dataset-link).

---

## **Workflow**
1. **Data Cleaning**:
   - Handle missing values and remove sensitive columns.
   - Engineer new features like `delay_duration`.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze delivery performance, sales trends, and customer behavior.
   - Visualize key metrics using Python libraries like Matplotlib and Seaborn.

3. **Predictive Modeling**:
   - Build a machine learning model to predict `Late_delivery_risk`.
   - Evaluate model performance using accuracy and classification reports.

4. **Dashboard Creation**:
   - Export cleaned data to Power BI.
   - Create interactive visualizations for delivery performance, sales insights, and discount analysis.

---

## **Installation**
To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/supply-chain-analytics.git
   cd supply-chain-analytics
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**
1. **Run the Jupyter Notebook**:
   - Open the notebook `supply_chain_analysis.ipynb` in Jupyter.
   - Execute each cell to perform data cleaning, EDA, and modeling.

2. **Export Data for Power BI**:
   - After running the notebook, the cleaned data will be saved as `processed_data.csv`.

3. **Build the Power BI Dashboard**:
   - Import `processed_data.csv` into Power BI.
   - Use the provided visualizations (e.g., bar charts, scatter plots) to create an interactive dashboard.

---

## **Results**
### **Key Insights**
1. **Delivery Performance**:
   - 15% of orders have a late delivery risk.
   - Expedited shipping has the lowest average delay duration.

2. **Sales Trends**:
   - Sales peak in December due to holiday shopping.
   - Higher discounts lead to increased order quantities but lower profit margins.

3. **Predictive Model**:
   - The Random Forest model achieved **85% accuracy** in predicting late delivery risks.

### **Dashboard Screenshot**
![Dashboard Screenshot](images/dashboard_screenshot.png)

---

## **Contributing**
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**
- Dataset sourced from [Kaggle](https://www.kaggle.com/).
- Special thanks to the open-source community for tools like Pandas, Scikit-learn, and Power BI.

---

## **Contact**
For questions or feedback, feel free to reach out:
- **Name**: Paunesh V
- **Email**: paunesh.datascientist@gmail.com
- **GitHub**: https://github.com/PAUNESH6206
