# Call Centre Dashboard in Power BI

This repository contains a project focused on creating an interactive Power BI dashboard for analyzing call center performance metrics. The project uses a dataset that captures key performance indicators (KPIs) of a call center, enabling users to monitor operations, identify trends, and make data-driven decisions.

## Project Overview

The objective of this project is to visualize call center data to provide actionable insights into operational efficiency, agent performance, and customer satisfaction. By leveraging Power BI, we created a dynamic dashboard with multiple pages for comprehensive analysis.

### Key Features:
- Real-time visualizations of key call center metrics.
- Detailed analysis of call volume, agent performance, and customer demographics.
- Multi-page navigation for enhanced data exploration.
- Identification of trends and outliers for decision-making.

## Dashboard Pages

1. **Home**:  
   - Provides an overview of various metrics such as call volume, agent performance, customer satisfaction, and operational efficiency.
   - Includes interactive visualizations for high-level insights into call center performance.

2. **Grid**:  
   - Displays detailed information about individual calls, such as:
     - **Reason for Call**: Categories of customer inquiries.
     - **Call Duration**: Time taken to handle each call.
     - **Customer Demographics**: Insights into customer profiles.
     - **Respnose Time**: Marks the response time according to SLA
   - Allows users to explore specific details using filters and interactive elements.

   Users can easily navigate between these pages within the dashboard to gain both high-level and detailed insights.

## Getting Started

### Prerequisites:
- **Power BI Desktop** to open and interact with the Power BI dashboard file.
- **Call Center Dataset**: The dataset capturing call center performance metrics (provided in the repository).

### Steps to Run:
1. **Clone or Download the Repository**:
   ```bash
   git clone https://github.com/HarshaEadara/Call-Centre-Dashboard-in-PowerBI.git
   ```
2. **Open Power BI**: Launch Power BI Desktop.
3. **Load the Dashboard:**
   - Open the `.pbix` file provided in the repository using Power BI Desktop.
4. **Explore the Dashboard:**
   - Navigate between the **Home** and **Grid** pages to explore both overall metrics and detailed call data.
   - Use filters and interactive features for a customized analysis.
   
### File Structure:
- `Call_Centre_Data.csv`: The dataset containing details of Netflix movies and TV shows.
- `Call_Centre_Dashboard.pbix`: Power BI dashboard containing the interactive visualizations.
- `Call center dashboard in PowerBI - Home.png`: Preview of the **Home** page in the dashboard.
- `Call center dashboard in PowerBI - GRID.png`: Preview of the **Grid** page in the dashboard.
- `README.md`: Project description (this file).

## Data Source

The dataset used in this project includes various performance metrics for a call center, such as:

- **Call Volume**: Number of calls received and handled.
- **Average Handling Time (AHT)**: Time spent on each call.
- **First Call Resolution (FCR)**: Percentage of calls resolved during the first interaction.
- **Agent Performance**: Metrics for evaluating individual agent efficiency.
- **Customer Satisfaction (CSAT)**: Ratings provided by customers post-interaction.
- **Call Details**: Information about call duration, reasons, and customer demographics.

## Visualizations

The Power BI dashboard provides the following key visualizations:

- **Call Volume Trends**: Track call volumes over time to identify peak periods.
- **Agent Performance Analysis**: Evaluate the efficiency of individual agents.
- **Customer Satisfaction Overview**: Visualize CSAT trends and identify areas for improvement.
- **Operational Metrics**: Insights into AHT, FCR, and other operational KPIs.
- **Call Details Grid**: Explore detailed data on individual calls, including reasons, durations, and customer demographics.


## Usage

This dashboard enables users to:

- **Monitor KPIs**: Keep track of critical metrics for call center performance.
- **Explore trends**: Identify patterns in call volumes, agent performance, and customer satisfaction.
- **Analyze detailed data**: Dive into specific call details using the Grid page.
- **Make data-driven decisions**: Use insights to optimize operations and improve customer experience.

## Contributions

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and create a pull request. Please ensure any pull requests follow the standard repository guidelines.
