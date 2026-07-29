# Adventure Works SSAS Multidimensional Cube

## Overview

This repository contains a **Microsoft SQL Server Analysis Services (SSAS) Multidimensional** project built on top of the **Adventure Works DW2019** data warehouse.

The goal of this project is to demonstrate the implementation of a multidimensional analytical model for sales analysis using the Microsoft BI stack.

---

## Technologies Used

* SQL Server 2022
* SQL Server Analysis Services (SSAS) – Multidimensional
* Visual Studio 2022
* Adventure Works DW2019

---

## Project Structure

```text
AdventureWorks-SSAS-Cube/
│
├── ScreenShots/
│   ├── cube-browser.png
│   ├── dimension-date.png
│   └── hierarchy-calendar.png
│
└── SSAS/
    ├── Adventure Works DW2019.cube
    ├── DimDate.dim
    ├── DimCustomer.dim
    ├── DimProduct.dim
    ├── DimGeography.dim
    └── DimEmployee.dim
```

---

## Implemented Features

* Multidimensional cube design
* Dimension modeling
* Calendar hierarchy
* Attribute relationships
* Sales analysis by time, customer, product, geography, and employee
* OLAP browsing and analytical exploration

---

## Dimensions

The project includes the following dimensions:

* **Date**
* **Customer**
* **Product**
* **Geography**
* **Employee**

---

## Analytical Capabilities

The cube supports analysis such as:

* Sales trend by year, quarter, and month
* Product performance analysis
* Customer sales analysis
* Geographic sales analysis
* Employee sales performance analysis

---

## Screenshots

Screenshots of the cube browser, dimensions, and hierarchies are available in the **`ScreenShots`** folder.

---

## How to Open the Project

1. Install **Visual Studio 2022**.
2. Install the **SQL Server Analysis Services Projects** extension.
3. Open the solution file in Visual Studio.
4. Deploy the project to a local or remote SSAS Multidimensional instance.
5. Process the database and browse the cube.

---

## Author

**Arshia Norouzi**

* GitHub: https://github.com/arshia-norouzi
* LinkedIn: https://www.linkedin.com/in/arshia-norouzi/
