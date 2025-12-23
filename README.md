# Vehicle-Expense-Tracking-Web-App

A local-ready **Vehicle Expense Tracking** web application built with **Blazor (.NET 8)** and **Microsoft SQL Server (MSSQL)**.  
Track multiple vehicles, log expenses (fuel, maintenance, etc.), and view reports including fuel consumption and vehicle comparisons.

---

## Key Features

- **Multiple Vehicles**: Add and manage as many vehicles as you want.
- **Expense Tracking**: Log unlimited expenses per vehicle (fuel, maintenance, repairs, insurance, etc.).
- **Expense Listing**: View and filter expense history per vehicle.
- **Fuel Consumption Report**: Using **fuel liters** and **odometer/km** data, view **L/100km** consumption statistics.
- **Yearly Insights**: Review yearly summaries and compare trends across years.
- **2-Vehicle Comparison**: Compare up to **two vehicles** side-by-side (costs, consumption, totals).
- **Local & Private**: Data is stored locally on your SQL Server instance.

---

## Tech Stack

- **Blazor Web App** (.NET 8)
- **C#**
- **Entity Framework Core (Code First + Migrations)**
- **Microsoft SQL Server (Local)**

---

## Prerequisites

- **.NET SDK 8.x**
- **SQL Server** (choose one)
  - SQL Server Express / Developer Edition
  - OR LocalDB (commonly installed with Visual Studio)
- (Recommended) **Visual Studio 2022**

---

## Getting Started (Local Setup)

### 1) Clone the repository

```bash
git clone https://github.com/Alperen-Tasdemir/Vehicle-Expense-Tracking-Web-App.git
cd Vehicle-Expense-Tracking-Web-App

