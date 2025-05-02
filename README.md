# TASK-8
# Power BI Sales Dashboard Project

##  Objective
Creating a basic **interactive dashboard** using Power BI that shows sales performance by:
- Product **Category**
- **Region**
- **Month-Year**

---

##  Tools Used
- **Power BI**
- Dataset: `Superstore_Sales.csv` (provided)

---

##  Dataset Preparation
1. **Imported CSV** into Power BI.
2. **Transformed Date**: Converted `Order Date` from `dd-mm-yyyy` to `MM-YYYY` format.
   - Added new column: `MonthYear`
   - Created a `SortMonth` column for correct time-based sorting.

---

##  Visuals Added
| Visualization | Details |
|---------------|---------|
| **Line Chart** | Average Sales by `MonthYear` |
| **Bar Chart** | Sum of Sales by `Region` |
| **Donut Chart** | Sum of Sales by `Category` |
| **Cards** | Count of Sales, Profit, Quantity, Category, and Cities |
| **Slicer**
