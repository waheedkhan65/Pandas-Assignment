# 🧠 Pandas Assignment - February Sales Data Analysis

This project is a hands-on assignment using the **Pandas** library in Python to analyze sales data from February 2015. The dataset (`sales-feb-2015.csv`) includes details such as sale date, company, product type, units sold, and more.

---

## 📁 Dataset Used
**File:** `sales-feb-2015.csv`  
**Key Columns:**
- `Date` (Timestamp of sale)
- `Company` (e.g., Hooli, Initech, etc.)
- `Product` (Software, Hardware, or Service)
- `Units` (Number of units sold)

---

## 🔧 Tasks Performed

### 🔢 Indexing
1. Loaded the CSV file and set the `Date` column as the DataFrame index.
2. Accessed the number of units sold on **February 5th, 2015 at 02:00:00** using both square bracket notation and `.loc`.
3. Created a new DataFrame with only `Company` and `Units` columns.

### ✂️ Slicing
4. Extracted all sales data from **Feb 3 to Feb 5**.
5. Displayed the **first 5 entries** in the dataset using slicing.
6. Used `.loc` to extract only rows where the company is **Hooli**.
7. Used `.iloc` to extract **rows 2 through 4**, and **columns 1 and 2**.

### 🔍 Filtering
8. Filtered rows where **more than 10 units** were sold.
9. Created a **boolean mask** to extract all rows where the product is **Software**.
10. Fetched rows where the product is **Hardware OR units > 15**.
11. Dropped any rows with **NaN values**.

### 🔄 Transforming
12. Created a new column `Revenue` using custom prices:
    - Software: `$350/unit`
    - Hardware: `$425/unit`
    - Service: `$275/unit`
13. Added a new column `DayOfWeek` to extract the weekday from the date.
14. Applied a **discount** to the revenue:
    - 5% discount for 15+ units
    - 10% discount for 20+ units
15. Created `CompanyUpper` (uppercase names) and `CompanyCode` (first 3 letters of company name).

---

## 🛠 How to Run the Code

Make sure you have Python and Pandas installed:

```bash
pip install pandas

```
🧑‍💻 Author
Waheed ur Rahman
BS Software Engineering Student
GitHub: @waheedkhan65
