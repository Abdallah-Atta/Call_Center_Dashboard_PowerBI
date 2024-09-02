# Call Center Dashboard in Power BI

This project is designed to create an interactive call center dashboard using Power BI. The dashboard provides a comprehensive overview of call center performance, including metrics such as the number of calls, agent performance, and customer satisfaction. Below are the steps to build the dashboard, from data import to creating KPIs.

## Project Overview

The dashboard displays key metrics such as total calls, answered calls, rejected calls, resolved/unresolved percentages, and more. It also provides insights into the performance of agents and the nature of the calls handled.

## Steps to Build the Dashboard

### 1. Importing Data into Power BI

- **Open Power BI** and navigate to the `Home` tab.
- Click on `Get Data` and choose your data source (e.g., Excel, SQL Server, etc.).
- Select the relevant tables or sheets containing the call center data.

### 2. Power Query: Data Cleaning and Transformation

Once the data is imported, you will be directed to Power Query for data preprocessing.

#### 2.1. Handling Data Types

- **Check Data Types**: Ensure that each column has the correct data type. For example, dates should be in `Date` format, numbers in `Decimal Number` or `Whole Number`, and text in `Text`.
- **Change Data Types** if necessary by clicking on the data type icon next to the column headers.

#### 2.2. Handling Null Values

- **Identify Null Values**: Use the `Transform` tab to filter out or identify columns with null values.
- **Replace Null Values**: Replace nulls with appropriate values (e.g., "Unknown" for text columns, "0" for numerical columns) using the `Replace Values` option.

#### 2.3. Removing Duplicates

- **Check for Duplicates**: Identify and remove duplicate rows by selecting the relevant columns and using the `Remove Duplicates` feature under the `Home` tab.

#### 2.4. Data Cleaning in Power Query

- **Filter Data**: Filter out any irrelevant or redundant data.
- **Split Columns**: Use the `Split Column` feature if you need to break down any complex fields into simpler columns (e.g., splitting dates into month and year).
- **Group Data**: Group data by certain criteria if needed, such as grouping by agent to see total calls handled by each.

### 3. Creating the Dashboard

#### 3.1. Designing the Layout

- **Choose a Theme**: Start by selecting a color theme that matches your organization’s branding.
- **Add Visuals**: Use a combination of bar charts, pie charts, line graphs, and tables to display the key metrics.

#### 3.2. Key KPIs to Display

- **Percentage of Calls Blocked**: Measure the percentage of calls that couldn't get through due to high call volume.
- **Average Handle Time (AHT)**: Track the average time an agent spends handling a call, including talk time and follow-up tasks.
- **Customer Effort Score (CES)**: Display the CES, which measures how much effort a customer has to put in to resolve their issue.
- **Net Promoter Score (NPS)**: Show the NPS, a metric that indicates customer loyalty and satisfaction.
- **Longest Call Hold**: Highlight the longest time a customer was on hold before speaking with an agent.
- **Average Call Length**: Track the average duration of all calls handled by the call center.

#### 3.3. Adding Filters and Slicers

- **Add Date Filters**: Use date slicers to allow users to filter the data by specific periods.
- **Agent and Call Type Filters**: Add slicers to filter the data based on the agent or the type of call.

### 4. Publishing the Dashboard

- **Publish to Power BI Service**: Once the dashboard is complete, publish it to Power BI Service for sharing with your team.
- **Set Up Automatic Refresh**: Ensure the data is automatically refreshed at set intervals to keep the dashboard up-to-date.

### 5. Dashboard Overview

The final dashboard includes:

- A summary of total calls, answered calls, rejected calls, and resolution rates.
- Visual breakdowns of calls by topics, such as contract-related issues, streaming issues, etc.
- Performance insights by agents, including the top-performing agent by answered calls.
- Monthly trends in total calls and call durations.
