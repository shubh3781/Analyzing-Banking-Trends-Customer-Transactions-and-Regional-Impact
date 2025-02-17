﻿# Analyzing-Banking-Trends-Customer-Transactions-and-Regional-Impact

---

# Project Title: Customer Transaction Analysis

## Overview

This project focuses on analyzing customer transaction data to extract meaningful insights. The project involves data cleaning, transformation, and analysis to understand various aspects of customer behavior, transaction patterns, and regional differences. The project uses multiple datasets, including user nodes, user transactions, and world regions.

## Table of Contents

- [Overview](#overview)
- [Data Description](#data-description)
- [Project Tasks](#project-tasks)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Data Description

### Files
1. **user_nodes_cleaned.csv**: Contains information about users and their associated regions.
2. **user_transactions_cleaned.csv**: Contains transaction details of users.
3. **world_regions.csv**: Contains information about different world regions.

### Columns

#### user_nodes_cleaned.csv
- `consumer_id`: Unique identifier for the consumer.
- `region_id`: Identifier for the region.
- `node_id`: Identifier for the node.
- `start_date`: The date when the consumer started.
- `end_date`: The date when the consumer ended.

#### user_transactions_cleaned.csv
- `transaction_id`: Unique identifier for the transaction.
- `consumer_id`: Unique identifier for the consumer.
- `transaction_date`: Date of the transaction.
- `transaction_amount`: Amount of the transaction.
- `transaction_type`: Type of transaction (e.g., deposit, withdrawal).

#### world_regions.csv
- `region_id`: Unique identifier for the region.
- `region_name`: Name of the region.

## Project Tasks

### Task 1: Data Import and Inspection
- Import datasets using Pandas.
- Inspect the data to understand its structure and contents.

### Task 2: Data Cleaning
- Handle missing values and duplicates.
- Rename columns for better clarity.
- Drop unnecessary columns.

### Task 3: Merging Datasets
- Merge user nodes and world regions datasets based on `region_id`.

### Task 4: Analyzing Transaction Data
- Import transaction data and inspect for null values.
- Calculate transaction statistics (e.g., average deposit amount).

### Task 5: Regional Analysis
- Analyze transaction counts by region.
- Join datasets to aggregate transaction data based on regions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook code.ipynb
   ```

2. Run the cells step-by-step to reproduce the analysis.

## Results

### Key Insights
- **Average Deposit Amount**: Calculated the average deposit amount per transaction type.
- **Transaction Counts by Region**: Analyzed the number of transactions across different regions.

### Visualizations
- Plots and charts representing transaction patterns and regional analysis.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Special thanks to the contributors and the open-source community.
- Acknowledge any external datasets or libraries used in the project.

---
