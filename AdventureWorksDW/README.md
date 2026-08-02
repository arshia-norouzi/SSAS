# AdventureWorks SSAS Project

This folder contains an **SSAS Multidimensional** project developed using the **AdventureWorksDW** sample database.

The project demonstrates the complete workflow of building an OLAP solution in SQL Server Analysis Services, including data source configuration, dimensions, hierarchies, cube design, and processing.

---

## Folder Structure

```text
AdventureWorks/
│
├── Analysis Services/
│   ├── AdventureWorksSSAS.sln
│   ├── AdventureWorksSSAS.dwproj
│   └── (other SSAS project files)
│
├── ScreenShots/
│   ├── README.md
│   └── *.png / *.jpg
│
└── README.md
```

---

## Analysis Services

The **Analysis Services** folder contains the Visual Studio solution and all SSAS project files required to open, edit, process, and deploy the cube.

### Environment

* **Visual Studio 2022**
* **SQL Server Analysis Services (Multidimensional)**
* **SQL Server 2022**
* Target server configured as: `.\MultiDim`

To open the project:

1. Open `AdventureWorksSSAS.sln` in Visual Studio.
2. Ensure SSAS Multidimensional extensions are installed.
3. Update the target server if necessary.
4. Process and deploy the project.

---

## ScreenShots

The **ScreenShots** folder contains screenshots documenting the development process and final cube design. Detailed descriptions of each screenshot are available in `ScreenShots/README.md`.

---

## Features Implemented

* Data Source
* Data Source View (DSV)
* Date Dimension
* Product Dimension
* Customer Dimension
* Geography Dimension
* Time Hierarchies
* Measure Groups
* Cube Design
* Attribute Relationships
* Cube Processing

---

## Learning Objectives

This project was created to practice:

* Star schema analysis
* Dimension modeling
* Hierarchy design
* Measure aggregation
* SSAS cube processing
* OLAP navigation and analysis

