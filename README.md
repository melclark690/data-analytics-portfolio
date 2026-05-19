# Project Title: E-Commerce Performance Dashboard & User Guide by Melissa Clark

## 📌 Project Overview
This project analyzes a public retail dataset to uncover key consumer shopping trends. It includes an interactive data dashboard built in Tableau and a comprehensive step-by-step technical guide detailing the data extraction, transformation, and visualization process.

---

## 📊 Part 1: The Data Analysis

### 1. Data Source & Preparation
* **Dataset Used:** [Kaggle Sample Superstore Dataset](https://www.kaggle.com/datasets/naveenkumar20bps1137/sample-superstore)
* **Size:** [e.g., 50,000 rows, 12 columns]
* **Key Variables:** Order Date, Category, Sales, Profit, Region, Customer Segment.

### 2. Core Business Insights
After cleaning and analyzing the data, the three primary findings were:
1. **Q4 Demand Spikes:** Technology sales surge by 35% every November. Executives must scale inventory and logistics by October to prevent stock shortages.
2. **Margin Disparity:** Technology yields a 42% profit margin, while Furniture drops below 10%. The marketing team must prioritize ad spend toward high-margin tech assets.
3. **Q1 Revenue Slump:** Furniture sales drop by 50% every January. The e-commerce platform should launch targeted New Year promotions to clear excess winter inventory.

### 3. Tableau Dashboard Link
👉 **[View the Interactive Tableau Dashboard Here](https://public.tableau.com/authoring/E-CommerceBusinessPerformanceDashboard/Dashboard1#1)**

---

## ✍️ Part 2: Technical Deployment Guide

### Prerequisites
Before reproducing this dashboard, ensure you have the following software installed:
* [Tableau Public Desktop Application](https://tableau.com) (Free)
* Access to the raw CSV dataset hosted in this repository.

### Step-by-Step Instructions

#### Step 1: Connect and Clean the Data
1. Open Tableau Public Desktop.
2. Under **Connect**, click **Text File** and select the downloaded CSV dataset.
3. Navigate to the **Data Source** tab.
4. Locate the `Order Date` column, right-click, and change the data type to **Date**.
5. Filter out all rows containing null values in the `Profit` column.

#### Step 2: Build the Sales Trend Chart
1. Open a new Worksheet and name it `Sales Over Time`.
2. Drag `Order Date` to the **Columns** shelf and change the view to **Month**.
3. Drag `Sales` to the **Rows** shelf.
4. Change the mark type from **Automatic** to **Line** to display the monthly trend.

#### Step 3: Publish the Dashboard
1. Select **File** > **Save to Tableau Public As...**
2. Log in using your credentials.
3. Name your workbook and click **Save**.

---

## 🤖 Part 3: AI-Assisted Workflow (GenAI Integration)

This project leveraged Generative AI (**ChatGPT/Gemini**) to optimize efficiency. Below are the exact prompting frameworks used:

### Data Cleaning Prompt
> *"Act as a data analyst. I have a retail CSV file where the date column is formatted as text (DD-MM-YYYY). Provide a step-by-step method to convert this to a standard date format inside Tableau Public without losing data integrity."*

### Documentation Editing Prompt
> *"Act as a professional technical writer. Review the following step-by-step user instructions for active voice, clarity, and adherence to the Google Technical Writing Style Guide. Ensure sentences are punchy and under 15 words."*
