# Superstore_Dashboard

# Superstore Data Analysis Dashboard

## Overview
This project is an interactive data analysis dashboard for Superstore sales data, built using Streamlit and Plotly. The dashboard provides comprehensive insights into sales performance, geographical distribution, and product category analysis.

## Features
- Interactive data exploration
- Multiple visualization types:
  - Bar charts
  - Pie charts
  - Line charts
  - Treemaps
  - Scatter plots
- Flexible filtering options:
  - Date range selection
  - Region filtering
  - State filtering
  - City filtering
- Data export functionality
- Detailed sales and profit analysis

## Technology Stack
- Python
- Streamlit
- Plotly
- Pandas
- Matplotlib

## Prerequisites
- Python 3.7+
- pip (Python package manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/pravin22kumar/superstore-analysis.git
cd superstore-analysis
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install streamlit plotly pandas matplotlib
```

## Running the Dashboard
```bash
streamlit run dashboard.py
```

## Dashboard Capabilities

### Visualizations
- Category-wise Sales Bar Chart
- Region-wise Sales Pie Chart
- Time Series Sales Analysis
- Hierarchical Sales Treemap
- Segment-wise Sales Pie Chart
- Sales vs. Profit Scatter Plot

### Filtering Options
- Date Range Selection
- Region Selection
- State Selection
- City Selection

### Data Export
- Download options for:
  - Category Sales
  - Region Sales
  - Time Series Data
  - Full Dataset

## Project Structure
```
superstore-analysis/
│
├── dashboard.py        # Main Streamlit dashboard script
├── Superstore.csv      # Sample dataset
└── README.md           # Project documentation
```

## Data Requirements
The dashboard expects a CSV file with columns:
- Order Date
- Region
- State
- City
- Category
- Sub-Category
- Segment
- Sales
- Profit
- Quantity

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Pravinkumar A -- Pravinkumar22005@gmail.com

Project Link: [https://github.com/pravin22kumar/Superstore_Dashboard]
