# AdventureWorks SSAS – Analysis Services

This folder contains the **SQL Server Analysis Services (SSAS) Multidimensional** project files for the AdventureWorks data warehouse.

The project was developed in **Visual Studio 2022** using **SQL Server Analysis Services (Multidimensional)** and demonstrates the implementation of a complete OLAP solution.

---

## Contents

```text
Analysis Services/
├── AdventureWorksSSAS.sln
├── AdventureWorksSSAS.dwproj
├── *.dim
├── *.cube
├── *.dsv
├── *.ds
└── other SSAS project files
```

---

## Development Environment

| Component     | Version          |
| ------------- | ---------------- |
| Visual Studio | 2022             |
| SQL Server    | 2022             |
| SSAS          | Multidimensional |
| Database      | AdventureWorksDW |

Target server configured in the project:

```text
.\MultiDim
```

---

## Implemented Objects

The project includes:

* Data Source
* Data Source View (DSV)
* Dimensions
* Attribute Relationships
* User Hierarchies
* Measure Groups
* Cube Design
* Cube Processing Configuration

---

## How to Open the Project

1. Install **Visual Studio 2022**.
2. Install **SQL Server Analysis Services Projects** extension.
3. Open `AdventureWorksSSAS.sln`.
4. Verify the target SSAS server name.
5. Build, process, and deploy the project.

---

## Purpose

This project is intended for learning and portfolio purposes and demonstrates practical skills in:

* Multidimensional modeling
* OLAP cube development
* Dimension and hierarchy design
* Aggregation and measure configuration
* SSAS deployment and processing

---

## Notes

* Ensure that the **AdventureWorksDW** database is available on SQL Server before processing the cube.
* Update connection strings if your SQL Server instance name differs from the default configuration.

