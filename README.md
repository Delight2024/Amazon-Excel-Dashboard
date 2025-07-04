# Amazon Product Review Analysis Dashboard

## 1. Introduction
Customer reviews provide rich insights into product performance, satisfaction, and pricing effectiveness. This project focuses on transforming Amazon product data into an interactive Excel dashboard to uncover patterns and answer business-critical questions.

## 2. Project Topic
**Product and Customer Review Analysis** on Amazon using Excel.

## 3. Project Overview
This dashboard helps identify:
-High-performing product categories  
-Discount trends and their effect on reviews  
-Average rating scores  
-Products with high review counts but low ratings
-

The aim is to guide sellers and decision-makers on price strategy, product improvement, and inventory focus.

## 4. Data Source
-Raw CSV file simulating Amazon review and pricing data  
-Dataset includes columns such as:
'Product ID', 'Product Name', 'Main Category', 'Discounted Price', 'Actual Price', 'Rating', 'Rating Count', 'Review Score', etc.
-

## 5. Data Cleaning
Performed in Excel:
-Removed blank rows and null values  
-Standardized formats (e.g., converted discount % to numeric)  
-Removed duplicate products where necessary  
-Created helper columns to support analysis:
  -'Discount % Viewable': to display readable percentages (e.g., 45%)  
  -'Rounded Rating': for clean grouping in visuals  
  -'Rating Review Score': composite score = Rating × Rating Count  
  -'Review Bucket': grouped total reviews into bins (e.g., 0–100, 101–200, etc.)  
  -'Price Bucket': categorized discounted prices into ranges  
  -'Main Category': extracted from the **Category** column to classify product type
  -

## 6. Exploratory Data Analysis (EDA)
The dashboard answers 14 business questions using Excel tools. While most calculations and summaries were done using **Pivot Tables**, the final visuals were built using appropriate charts for easy interpretation.

-Questions **4 and 14**: Data was analyzed using **Excel Tables**, and then **charts were created** to represent the results in the dashboard  
-Question **11**: Explored using a **Scatter Plot** to analyze the relationship between price and rating  
-All other questions used **Pivot Tables & Charts**  
-Visuals were arranged in sequence based on question order in the **‘Amazon Dashboard’** sheet

## 7. Recommendations
-Focus marketing on products with high discounts and strong reviews  
-Reassess low-rated products with high visibility  
-Analyze categories with poor performance for improvement or removal  
-Continue tracking discount impact on future reviews
-

## 8. Conclusion
This Excel dashboard simplifies Amazon product data into clear, actionable insights. It supports better inventory decisions, promotional strategies, and customer satisfaction tracking.
