# 📦 Supply Chain Analysis & Logistics Dashboard

<img width="2560" height="1513" alt="image" src="https://github.com/user-attachments/assets/5ac7111f-d36d-4560-97a1-9bed3252fb18" />


![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Supply Chain](https://img.shields.io/badge/Supply_Chain-FF6B6B?style=for-the-badge&logo=buffer&logoColor=white)

![Dataset](https://img.shields.io/badge/SKUs-100-blue)
![Revenue](https://img.shields.io/badge/Revenue-₹577.6K-green)
![Suppliers](https://img.shields.io/badge/Suppliers-5-orange)
![Status](https://img.shields.io/badge/Status-Complete-success)

## 📊 Project Overview

This comprehensive supply chain analytics project analyzes logistics operations, supplier performance, inventory management, and distribution efficiency across multiple product categories. The analysis covers **100 SKUs** with detailed insights into procurement, manufacturing, quality control, and shipping operations.

As a Data Analyst, I've developed interactive Power BI dashboards to visualize supply chain metrics, identify bottlenecks, and optimize operational efficiency across the entire logistics network.

## 🎯 Key Findings

### 💰 Financial Performance

| Metric | Value |
|--------|-------|
| **Total Revenue** | ₹577,604.82 |
| **Average Revenue per SKU** | ₹5,776.05 |
| **Total Manufacturing Costs** | ₹4,726.67 |
| **Total Shipping Costs** | ₹554.81 |
| **Estimated Profit** | ₹572,323.33 |
| **Profit Margin** | 99.1% |

**Key Insight**: Exceptional profit margins indicate highly efficient operations with low manufacturing and shipping costs relative to revenue.

### 🏷️ Product Portfolio Analysis

| Product Type | SKUs | Revenue | % of Total |
|--------------|------|---------|------------|
| **Skincare** | 40 (40.0%) | ₹241,628 | 41.8% |
| **Haircare** | 34 (34.0%) | ₹174,455 | 30.2% |
| **Cosmetics** | 26 (26.0%) | ₹161,521 | 28.0% |

**Key Insight**: Skincare dominates both product count and revenue generation, representing the most significant segment in the portfolio.

### 📈 Sales Performance

- **Total Products Sold**: 46,099 units
- **Average Sales per SKU**: 461 units
- **Best Performing SKU**: 996 units sold
- **Product Availability**: Average 47.8% stock availability

### 🏭 Supplier Network Analysis

**Supplier Distribution**:
- **Supplier 1**: 27 SKUs (27.0%) - Largest partner
- **Supplier 2**: 22 SKUs (22.0%)
- **Supplier 4 & 5**: 18 SKUs each (18.0%)
- **Supplier 3**: 15 SKUs (15.0%)

**Top Supplier Locations**:

| City | SKUs | Percentage |
|------|------|------------|
| Kolkata | 25 | 25.0% |
| Mumbai | 22 | 22.0% |
| Chennai | 20 | 20.0% |
| Bangalore | 18 | 18.0% |
| Delhi | 15 | 15.0% |

**Key Insight**: Supplier network is well-distributed across major Indian cities, with Kolkata serving as the primary hub.

### ⏱️ Lead Time & Efficiency Metrics

| Metric | Value |
|--------|-------|
| **Average Lead Time** | 16.0 days |
| **Median Lead Time** | 17 days |
| **Lead Time Range** | 1-30 days |
| **Avg Manufacturing Lead Time** | 14.8 days |
| **Total Order-to-Delivery Time** | ~30.8 days |

**Key Insight**: Relatively long lead times suggest opportunities for process optimization to improve time-to-market.

### 🚚 Logistics & Transportation

#### Shipping Carrier Performance

| Carrier | Shipments | Market Share |
|---------|-----------|--------------|
| **Carrier B** | 43 | 43.0% |
| **Carrier C** | 29 | 29.0% |
| **Carrier A** | 28 | 28.0% |

#### Transportation Modes

```
Road:  29 shipments (29.0%) - Most common
Rail:  28 shipments (28.0%) 
Air:   26 shipments (26.0%)
Sea:   17 shipments (17.0%) - Cost-effective for bulk
```

#### Shipping Routes Distribution
- **Route A**: 43% - Primary corridor
- **Route B**: 37% - Secondary route
- **Route C**: 20% - Tertiary route

**Cost Analysis**:
- Average Shipping Cost: ₹5.55 per shipment
- Total Shipping Costs: ₹554.81
- Shipping costs represent only 0.1% of total revenue

**Key Insight**: Balanced transportation mix optimizes for speed and cost, with road and rail dominating for domestic logistics.

### 🔍 Quality Control & Inspection

| Quality Metric | Value |
|----------------|-------|
| **Average Defect Rate** | 2.28% |
| **Median Defect Rate** | 2.14% |
| **Defect Range** | 0.02% - 4.94% |
| **Best Quality SKU** | 0.02% defects |

#### Inspection Status Breakdown

```
Pending:  41 SKUs (41.0%) - Awaiting inspection
Fail:     36 SKUs (36.0%) - Quality issues identified
Pass:     23 SKUs (23.0%) - Meets standards
```

**Critical Insight**: 36% failure rate indicates significant quality control challenges requiring immediate attention and supplier performance reviews.

### 📦 Inventory Management

| Metric | Value |
|--------|-------|
| **Average Stock Level** | 47.8 units |
| **Median Stock Level** | 48 units |
| **Low Stock Items** | 27 SKUs (27%) |
| **Out of Stock** | 1 SKU |
| **Overstock (>90 units)** | 8 SKUs |

**Key Insight**: 27% of inventory is running low, requiring improved demand forecasting and reorder point optimization.

### 👥 Customer Demographics

| Demographic | SKUs Targeted | Percentage |
|-------------|---------------|------------|
| Unknown | 31 | 31.0% |
| Female | 25 | 25.0% |
| Non-binary | 23 | 23.0% |
| Male | 21 | 21.0% |

**Key Insight**: Large "Unknown" category suggests need for better customer data collection and segmentation.

## 📁 Repository Contents

```
supply-chain-analysis/
│
├── supply_chain_analaysis_and_logistic.pbix  # Power BI Dashboard
├── supply_chain_data.csv                     # Main dataset (100 SKUs)
├── Supplier_Performance.csv                  # Supplier metrics
├── README.md                                 # Project documentation
└── visuals/                                  # Dashboard screenshots
```

## 🔍 Analysis Methodology

1. **Data Collection**: Aggregated data from 5 suppliers across 5 major cities
2. **Data Processing**: Cleaned and validated 100 SKU records with 24 attributes per product
3. **Visualization**: Built interactive Power BI dashboards for multi-dimensional analysis
4. **KPI Development**: Established metrics for supplier performance, quality, and logistics efficiency
5. **Insights Generation**: Identified bottlenecks, cost optimization opportunities, and quality issues

## 📊 Dashboard Features

The Power BI dashboard includes:

### 📈 Executive Dashboard
- Revenue overview and profitability metrics
- Sales performance by product type
- Cost breakdown and margin analysis

### 🏭 Supplier Performance
- Supplier-wise revenue contribution
- Lead time comparison across suppliers
- Quality metrics and defect rate tracking
- Geographic distribution of suppliers

### 🚚 Logistics Analytics
- Shipping carrier performance comparison
- Transportation mode optimization
- Route efficiency analysis
- Shipping cost trends and forecasting

### 🔍 Quality Management
- Inspection results dashboard
- Defect rate analysis by supplier and product
- Quality trend tracking over time
- Root cause analysis visualization

### 📦 Inventory Dashboard
- Stock level monitoring
- Low stock alerts
- Inventory turnover ratios
- Reorder point recommendations

### ⏱️ Operational Efficiency
- Lead time analysis
- Order fulfillment metrics
- Manufacturing cycle time
- End-to-end process timeline

## 🛠️ Tools & Technologies

- **Power BI Desktop** - Advanced data visualization and DAX formulas
- **Python** - Data preprocessing and statistical analysis
- **CSV** - Data storage and integration
- **DAX** - Custom measures and KPIs
- **Power Query** - Data transformation and modeling

## 📈 Business Recommendations

Based on comprehensive analysis:

### 🎯 Priority Actions

1. **Quality Improvement Initiative**
   - Address 36% inspection failure rate through supplier quality audits
   - Implement stricter quality control checkpoints
   - Establish supplier performance scorecards

2. **Inventory Optimization**
   - Implement automated reorder points for 27 low-stock items
   - Reduce overstock in 8 SKUs to free up working capital
   - Deploy predictive analytics for demand forecasting

3. **Lead Time Reduction**
   - Negotiate with suppliers to reduce 16-day average lead time
   - Optimize manufacturing processes to cut 14.8-day production cycle
   - Target 25% reduction in total order-to-delivery time

4. **Supplier Diversification**
   - Balance dependence on Supplier 1 (27% of portfolio)
   - Develop backup suppliers for critical SKUs
   - Negotiate volume discounts with top performers

5. **Route Optimization**
   - Analyze Route C inefficiencies (only 20% usage)
   - Consider air freight for high-value, time-sensitive products
   - Negotiate better rates with Carrier B (43% market share)

6. **Customer Data Enhancement**
   - Reduce 31% "Unknown" demographic classification
   - Implement better customer profiling systems
   - Enable targeted marketing based on demographics

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop ([Download](https://powerbi.microsoft.com/desktop/))
- Windows 10 or later
- 4GB RAM minimum (8GB recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Udhayanithi007/Supply-Chain-Analysis.git
cd Supply-Chain-Analysis
```

2. Open the Power BI file:
```bash
# Double-click supply_chain_analaysis_and_logistic.pbix
```

3. Refresh data connections:
- Navigate to **Home** → **Refresh**
- Verify CSV file paths if needed

## 📊 Data Schema

### Supply Chain Data (supply_chain_data.csv)

| Column | Type | Description |
|--------|------|-------------|
| Product type | String | Category (Skincare/Haircare/Cosmetics) |
| SKU | String | Stock Keeping Unit identifier |
| Price | Float | Product price (INR) |
| Availability | Integer | Stock availability (%) |
| Number of products sold | Integer | Units sold |
| Revenue generated | Float | Total revenue (INR) |
| Customer demographics | String | Target demographic |
| Stock levels | Integer | Current inventory count |
| Lead times | Integer | Days from order to delivery |
| Shipping carriers | String | Logistics provider |
| Shipping costs | Float | Shipping expense (INR) |
| Supplier name | String | Supplier identifier |
| Location | String | Supplier city |
| Manufacturing costs | Float | Production cost (INR) |
| Defect rates | Float | Quality defect percentage |
| Inspection results | String | Pass/Fail/Pending |
| Transportation modes | String | Road/Rail/Air/Sea |
| Routes | String | Shipping route identifier |

### Supplier Performance (Supplier_Performance.csv)

| Column | Type | Description |
|--------|------|-------------|
| Supplier_Name | String | Supplier identifier |
| Cost_per_Unit_INR | Integer | Unit cost in INR |
| Lead_Time_Days | Integer | Delivery lead time |
| Defect_Rate_Percent | Integer | Quality defect rate |

## 🎓 Skills Demonstrated

- **Supply Chain Analytics** - End-to-end logistics analysis
- **Power BI Development** - Complex dashboard creation with DAX
- **Data Modeling** - Relational data structure design
- **KPI Development** - Custom business metrics creation
- **Statistical Analysis** - Trend analysis and forecasting
- **Operational Excellence** - Process optimization insights
- **Quality Management** - Six Sigma methodologies
- **Inventory Optimization** - Stock level management
- **Supplier Management** - Vendor performance evaluation

## 📸 Dashboard Previews

*Screenshots of the Power BI dashboards would be included here*

## 🔄 Future Enhancements

- [ ] Machine learning for demand forecasting
- [ ] Real-time inventory tracking integration
- [ ] Automated supplier scorecard system
- [ ] Predictive maintenance for logistics
- [ ] IoT integration for shipment tracking
- [ ] Advanced cost optimization algorithms

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💼 About the Analyst

**Data Analyst** | Supply Chain & Operations Analytics Specialist

- **GitHub**: [@Udhayanithi007](https://github.com/Udhayanithi007)
- **LinkedIn**: [Connect with me](https://www.linkedin.com/in/udhayanithi007)
- **Portfolio**: [View my work](https://yourportfolio.com)
- **Email**: nithiudhaya56@gmail.com

## 📧 Contact

For questions, collaboration, or consulting opportunities:
- Open an issue in this repository
- Email: nithiudhaya56@gmail.com
- LinkedIn: [Your Profile](https://linkedin.com/in/udhayanithi007)

## 🌟 Acknowledgments

- Supply chain data providers
- Power BI community for visualization best practices
- Logistics and operations management experts
- Open-source data analytics community

---

**⭐ If you find this project useful for supply chain optimization, please star the repository!**

*Last Updated: February 2026*

## 📚 Additional Resources
- [Power BI Best Practices](https://docs.microsoft.com/power-bi)
