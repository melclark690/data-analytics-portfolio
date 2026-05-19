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
Before reproducing this dashboard, ensure you have the following requirements met:
* A modern web browser (Google Chrome, Microsoft Edge, or Safari).
* A free [Tableau Public Profile Account](https://tableau.com).
* The downloaded `SampleSuperstore.csv` dataset hosted in this repository.

### Step-by-Step Instructions

#### Step 1: Upload Data to Tableau Web Authoring
1. Log into your account on the [Tableau Public Homepage](https://tableau.com).
2. Click **Create** in the top navigation menu, then select **Web Authoring**.
3. Drag and drop your downloaded `SampleSuperstore.csv` file into the upload window.
4. Click the blue **Sheet 1** button in the bottom right corner to open your workspace.

#### Step 2: Build the Category Sales Trend Chart
1. Locate the **Data Pane** on the left side of the screen.
2. Drag the `Order Date` column and drop it directly onto the **Columns** shelf at the top.
3. Click the downward arrow on the `YEAR(Order Date)` pill and select **Month** (continuous format).
4. Drag the `Sales` column from the Data Pane and drop it onto the **Rows** shelf.
5. Drag the `Category` column and drop it onto the **Color** square inside the Marks card.

#### Step 3: Publish the Dashboard
1. Select **File** > **Save to Tableau Public As...**
2. Log in using your credentials.
3. Name your workbook and click **Save**.

---

## 🤖 Part 3: AI-Assisted Workflow (GenAI Integration)

This project used Generative AI to accelerate data analysis and refine technical documentation structure. Below are the specific prompting workflows utilized:

### 1. Business Logic Engineering (Google Gemini)
Used to extract core executive insights from raw dataset trend behaviors:
> *"I have built a Tableau line chart using the Sample Superstore dataset showing Monthly Sales Trends broken down by Category (Technology, Furniture, Office Supplies). I noticed that Technology spikes every November, Furniture drops in January, and Tech has the highest overall margins. Act as a data analyst and give me 3 professional, bulleted business insights explaining why these trends matter to an e-commerce executive."*

### 2. Editorial Optimization (ChatGPT)
Used to transform raw business insights into clear, concise documentation that meets enterprise style criteria:
> *"Act as a senior technical writer. Rewrite these data insights to strictly adhere to the Google Technical Writing Style Guide. Make the sentences punchy, use the active voice, keep them under 15 words per bullet point, and format them perfectly in Markdown for a GitHub README file."*
