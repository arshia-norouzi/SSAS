# SSAS Project Files

This folder contains the **SQL Server Analysis Services (SSAS) Multidimensional** project files for the **Adventure Works DW2019** analytical cube.

## Included Files

* `MultiDimensionalProject2.sln` – Visual Studio solution file
* `MultiDimensionalProject2.dwproj` – SSAS project file
* `Adventure Works DW2019.cube` – Cube definition
* `DimDate.dim` – Date dimension
* `DimCustomer.dim` – Customer dimension
* `DimProduct.dim` – Product dimension
* `DimGeography.dim` – Geography dimension
* `DimEmployee.dim` – Employee dimension

## Project Purpose

The project implements a multidimensional analytical model designed for:

* Sales analysis
* Customer analysis
* Product performance analysis
* Geographic sales analysis
* Time-based analysis using calendar hierarchies

## Requirements

To open and run this project you need:

* **Visual Studio 2022**
* **SQL Server Analysis Services Projects** extension
* Access to an **SSAS Multidimensional** instance
* **Adventure Works DW2019** data warehouse database

## How to Open

1. Open `MultiDimensionalProject2.sln` in Visual Studio.
2. Build and deploy the project to an SSAS instance.
3. Process the database.
4. Browse the cube in SSAS.

## Notes

This folder contains only the SSAS project artifacts. Screenshots and documentation are stored in the repository root under the `ScreenShots` folder.
