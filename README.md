# Data Preparation and Cleaning

## Project Objective

The objective of this project is to prepare and clean raw order data using Microsoft Excel before performing further data analysis.

## Dataset

The dataset contains order-related information such as:

- Order ID
- Date
- Customer ID
- Product
- Quantity
- Unit Price
- Shipping Address
- Payment Method
- Order Status
- Tracking Number
- Items in Cart
- Coupon Code
- Referral Source
- Total Price

## Data Cleaning Tasks Performed

### 1. Missing Value Check
Checked the dataset for blank or missing values.

### 2. Duplicate Check
Checked Order IDs and records for duplicate entries.

### 3. Extra Space Check
Used Excel's TRIM function to identify and remove unnecessary spaces.

### 4. Text Standardization
Used PROPER/TRIM where required to make text formatting consistent.

### 5. Date Formatting
Checked and standardized the date format and arranged dates chronologically where required.

### 6. Data Validation
Checked numeric fields such as Quantity, Unit Price and Total Price for valid values.

### 7. Formatting
Adjusted row height and column width using AutoFit to improve readability.

## Excel Functions Used

- TRIM()
- PROPER()
- UPPER()
- LOWER()
- COUNTIF()
- COUNTBLANK()
- IF()
- ISNUMBER()
- ROUND()

## Files Included

- `Raw_Data.xlsx` – Original raw dataset
- `Cleaned_Data.xlsx` – Prepared and cleaned dataset

## Outcome

The raw dataset was checked and prepared for further analysis. The cleaned dataset can be used as the input for subsequent data analysis and SQL analysis.
