# Superstore Sales Dashboard — Power BI

## Project Overview

This project is an interactive Sales Analytics Dashboard developed using Microsoft Power BI. The dashboard analyzes Superstore sales data to identify trends in sales, profit, customers, products, categories, regions, and segments.

## Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX
* Data Modelling
* Star Schema
* Excel

## Project Features

* Interactive Sales Dashboard
* Detailed Sales Analysis page
* Customer Details drill-through page
* Page navigation
* Interactive slicers
* KPI cards
* Sales and profit analysis
* Customer and product analysis
* Date-based analysis
* Data model with fact and dimension tables

## Data Preparation

Power Query was used for:

* Data type correction
* Data cleaning
* Handling duplicates and null values
* Creating conditional columns
* Splitting customer names
* Creating sales categories

## Data Model

The project uses a star-schema approach with:

* Orders fact table
* Customer dimension
* Product dimension
* Date dimension

Relationships were created between the fact and dimension tables to support interactive analysis.

## DAX

DAX measures were created for key business metrics including:

* Total Sales
* Total Profit
* Total Orders
* Category and region-based sales analysis
* Filtered calculations using `CALCULATE`
* Percentage calculations

## Dashboard Pages

### 1. Sales Dashboard

Provides an overview of important sales and profit metrics through KPI cards and charts.

### 2. Detailed Sales Analysis

Provides interactive analysis using slicers for:

* Region
* Category
* Segment
* Date

### 3. Customer Details

A drill-through page that provides customer-level analysis.

## Key Insights

The dashboard was used to explore:

* Sales and profit performance across categories
* Regional sales performance
* Customer-level performance
* Product performance
* Sales trends over time
* Differences between sales and profitability

## Screenshots

### Sales Dashboard

![Sales Dashboard](screenshots/sales-dashboard.png)

### Detailed Sales Analysis

![Detailed Sales Analysis](screenshots/detailed-sales-analysis.png)

### Customer Details

![Customer Details](screenshots/customer-details.png)

### Data Model

![Data Model](screenshots/data-model.png)

## Project Objective

The objective of this project was to build an interactive business intelligence dashboard and demonstrate practical skills in data cleaning, data modelling, DAX, visualization, filtering, drill-through analysis, and dashboard design.
