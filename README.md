# PhonePe Transaction Insights 📱💰

> A comprehensive data analytics project analyzing PhonePe's digital payment ecosystem to derive actionable business intelligence for fintech strategic decision-making.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![SQL](https://img.shields.io/badge/SQL-SQLite-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 🚀 Project Overview

This project analyzes PhonePe's transaction data to uncover insights about digital payment trends, user behavior, and market penetration across India. Using advanced data analytics, SQL optimization, and interactive visualizations, we deliver business intelligence that drives strategic decisions in the competitive fintech landscape.

---

### 🎯 Business Objectives

-   **Customer Segmentation**: Identify distinct user groups for targeted marketing.
-   **Fraud Detection**: Analyze transaction patterns to prevent fraudulent activities.
-   **Geographic Insights**: Map payment trends for regional strategy development.
-   **Performance Analytics**: Evaluate payment category popularity for investment decisions.
-   **User Engagement**: Monitor activity patterns to enhance retention.
-   **Insurance Analytics**: Optimize insurance product offerings.

---

## 📊 Key Features

### Data Processing Pipeline

-   **Automated data extraction** from PhonePe Pulse GitHub repository.
-   **Comprehensive ETL pipeline** with error handling and validation.
-   **SQLite database optimization** with proper indexing and relationships.
-   **Memory-efficient processing** handling large datasets seamlessly.

### Analytics Dashboard

-   **Interactive Streamlit application** for real-time data exploration.
-   **Geographic visualizations** with state and district-level insights.
-   **Time-series analysis** revealing seasonal and growth patterns.
-   **Top performers identification** across states, districts, and pincodes.

### Business Intelligence

-   **KPI tracking and monitoring** for key business metrics.
-   **Trend analysis** for strategic planning and forecasting.
-   **Comparative analysis** across regions and time periods.
-   **Actionable insights** with clear business recommendations.

---

## 🛠️ Technology Stack

| Component         | Technology                  | Purpose                             |
| ----------------- | --------------------------- | ----------------------------------- |
| **Data Processing** | Python (Pandas, NumPy)      | ETL pipeline and data manipulation  |
| **Database** | SQLite                      | Lightweight storage and query optimization |
| **Visualization** | Streamlit, Plotly, Matplotlib | Interactive dashboards and charts |
| **Version Control** | Git                         | Code management and collaboration   |
| **Documentation** | Jupyter Notebook            | Analysis documentation and presentation |

---

## 📁 Project Structure

phonepe-transaction-insights/
├── pulse/                          # Raw PhonePe Pulse data
├── sample_data/                    # Sample datasets for quick testing
├── customer_segments.csv           # User segmentation dataset
├── insurance_trends.csv            # Insurance adoption and trends
├── payment_methods.csv             # Payment category distribution
├── phonepe_dashboard.py            # Streamlit dashboard application
├── phonepe_pulse_database.db       # Main SQLite database
├── phonepe_pulse_database.db-shm   # Database shared memory file
├── phonepe_pulse_database.db-wal   # Database write-ahead log
├── top_states_by_amount.csv        # Top states ranked by transaction value
├── transaction_trends_yearly.csv   # Yearly transaction trends
└── user_engagement.csv             # User behavior and engagement data

---

## 🚀 Quick Start

### Prerequisites

-   Python 3.8 or higher
-   Git
-   SQLite database
-   4GB+ RAM recommended

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/phonepe-transaction-insights.git](https://github.com/yourusername/phonepe-transaction-insights.git)
    cd phonepe-transaction-insights
    ```
2.  **Create a virtual environment**
    ```bash
    python -m venv phonepe_env
    source phonepe_env/bin/activate  # On Windows: phonepe_env\Scripts\activate
    ```
3.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the Streamlit dashboard**
    ```bash
    streamlit run phonepe_dashboard.py
    ```

---

## 📊 Data Sources

### Primary Dataset

-   **Source**: PhonePe Pulse GitHub Repository
-   **Format**: JSON → Converted to CSV & SQLite
-   **Coverage**: 2018–2024 transaction and user data
-   **Size**: 500K+ records across multiple datasets

### Dataset Categories

-   **Aggregated Data**: Transaction summaries and user metrics
-   **Map Data**: Geographic distribution at state and district levels
-   **Top Data**: Rankings of top-performing entities

---

## 🔍 Key Insights Discovered

### Transaction Trends

-   45% year-over-year growth in digital payment adoption.
-   Q3 peak performance consistent across multiple years.
-   Metro cities saturation with rural markets emerging.

### Geographic Analysis

-   Maharashtra leads in transaction value and volume.
-   South India dominance in per-capita adoption.
-   Northeast potential for expansion identified.

### User Behavior

-   Android users represent 85%+ of the user base.
-   Peer-to-peer transfers dominate transaction categories.
-   Weekend usage spikes indicate leisure spending patterns.

---

## 🎨 Dashboard Features

-   Real-time filtering by state, year, quarter, and category.
-   Geographic heat maps showing regional performance.
-   Drill-down capabilities from state to district to pincode level.
-   Export functionality for reports and presentations.

---

## 📋 Business Applications

-   Market penetration analysis for expansion decisions.
-   Resource allocation optimization based on regional performance.
-   Product development prioritization using usage patterns.
-   Risk management through anomaly detection.

---

## 📚 Documentation

-   Insights Report (PDF)
-   Technical Documentation (Markdown)
-   Presentation Slides (PPTX)

---

## 🤝 Contributing

We welcome contributions to enhance this project!
Please fork, follow coding standards, and submit pull requests.

## 📄 License

This project is licensed under the MIT License – see the `LICENSE` file for details.

---

*Built with ❤️ for the fintech community*

*Transforming payment data into business intelligence • Driving data-driven decisions • Enabling strategic growth*
