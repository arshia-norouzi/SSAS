# Adventure Works SSAS Multidimensional Cube

## Overview

This project demonstrates the implementation of a **Microsoft SQL Server Analysis Services (SSAS) Multidimensional** cube based on the **Adventure Works DW2019** data warehouse.

The objective of the project is to build a multidimensional analytical model for sales analysis using dimensions, hierarchies, and measure groups.

---

## Technologies Used

* SQL Server 2022
* SQL Server Analysis Services (SSAS) – Multidimensional
* Visual Studio 2022
* Adventure Works DW2019

---

## Project Structure

* **SSAS**: Contains the SSAS solution, cube definition, and dimension files.
* **ScreenShots**: Contains screenshots of the project design, dimensions, hierarchies, and cube configuration.

---

## Implemented Features

* Multidimensional cube design
* Dimension modeling
* Calendar hierarchy
* Geography hierarchy
* Product hierarchy
* Role-playing Date dimensions
* Measure groups and dimension usage configuration
* OLAP analytical model for sales analysis

---

## Dimensions

The cube includes the following dimensions:

* Date
* Customer
* Product
* Geography
* Employee

---

## Screenshots Description

### Data Source View

Displays the multidimensional data model and relationships between fact tables and dimension tables.

### Cube Dimension Usage

Shows the relationship between measure groups and dimensions, including multiple date roles such as Order Date, Ship Date, and Due Date.

### Date Dimension Hierarchy

Demonstrates the calendar hierarchy implemented as **Year → Semester → Quarter → Month**.

### Customer Dimension

Shows customer-related attributes used for customer segmentation and sales analysis.

### Employee Dimension

Shows employee-related attributes used for organizational and sales performance analysis.

### Geography Dimension Hierarchy

Demonstrates the geographic hierarchy implemented as **Country → State/Province → City**.

### Product Dimension Hierarchy

Shows the product hierarchy implemented as **Category → Subcategory → Product**.

---

## Analytical Capabilities

The cube supports analysis such as:

* Sales trend analysis by year, quarter, and month
* Product performance analysis
* Customer sales analysis
* Geographic sales analysis
* Employee sales performance analysis

---

## How to Open the Project

1. Install **Visual Studio 2022**.
2. Install the **SQL Server Analysis Services Projects** extension.
3. Open the solution file.
4. Deploy the project to an SSAS Multidimensional instance.
5. Process the database and browse the cube.

---

## Author

**Arshia Norouzi**

* GitHub: https://github.com/arshia-norouzi
* LinkedIn: https://www.linkedin.com/in/arshia-norouzi/
