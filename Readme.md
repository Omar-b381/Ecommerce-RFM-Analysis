# 🛒 E-Commerce RFM & Sales Analysis

## 📌 Project Description
This project analyzes e-commerce transactions to extract **business insights** including:
- **RFM Analysis** to segment customers into VIP, Potential Loyalists, At Risk, and Lost.
- **Sales & Returns Analysis** to calculate net revenue and top-performing products.
- **Monthly KPIs** such as Revenue, Quantity, Number of Transactions, and AOV.
- **Customer Behavior Analysis** to support **marketing and retention strategies**.

> The project demonstrates a complete **data analytics workflow** using Python & Pandas,  
> transforming raw e-commerce data into actionable business intelligence.

---

## 📂 Project Structure
```
Ecommerce-RFM-Analysis/
│
├── data/                # Dataset (if small) or link in README
├── notebooks/           # Jupyter Notebooks for analysis
├── scripts/             # Python scripts for data processing
├── outputs/             # Charts & figures
│
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
└── .gitignore           # Ignore unnecessary files
```

---

## 🚀 How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/USERNAME/Ecommerce-RFM-Analysis.git
cd Ecommerce-RFM-Analysis
```

2. **Create virtual environment (recommended)**
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run analysis**
- Open the notebook:
```bash
jupyter notebook notebooks/analysis.ipynb
```

---

## 📊 Key Features

### 1️⃣ RFM Analysis
- Segments customers into:
  - **VIP Customers** → Recent, Frequent, High spenders  
  - **Potential Loyalists** → Frequent but not recent  
  - **At Risk** → High past value, no recent activity  
  - **Lost Customers** → Old and infrequent  
- Generates RFM table with scoring and segmentation.

### 2️⃣ Sales & Returns Analysis
- Net revenue calculation including returns.  
- Top-selling and most-returned products.  
- Monthly KPI dashboard with:
  - Revenue
  - Transactions
  - Quantity
  - Average Order Value (AOV)

### 3️⃣ Visualizations
- **Monthly Revenue (Purchases vs Returns)** – Stacked Bar Chart  
- **Customer Segments Distribution** – Pie & Bar Charts  
- **RFM Heatmap** – Recency vs Frequency vs Monetary  

> 💡 Screenshots or charts can be added to `outputs/` folder.

---

## 📁 Dataset
- Original data: E-commerce transactions (InvoiceNo, CustomerID, Quantity, UnitPrice, InvoiceDate)
- If the dataset is large:
  - Provide a **Google Drive / Kaggle link** here.

---

## 🛠 Tech Stack
- Python 3.11+
- Pandas, NumPy
- Matplotlib, Seaborn
- Humanize (for friendly numbers)
- mlxtend (for association rules)
- Jupyter Notebook

---

## 📈 Sample Results

**RFM Heatmap Example:**
```
Frequency ↑
    +-----------------------------+
    |                             |
    |           VIP                |
    |                             |
    +-----------------------------+ → Recency
```

---

## 🤝 Contributing
Contributions and suggestions are welcome!  
If you find a bug or have an improvement idea, feel free to open an **Issue** or **Pull Request**.

---

## 📬 Connect with Me
- **LinkedIn:** [Omar Ahmed](https://www.linkedin.com/in/omarbadrdata/)  
- **Gmail:** [omar.work381@gmial.com](omar.work381@gmail.com)  

---

**⭐ If you found this project useful, please give it a star on GitHub!**
