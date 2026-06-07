# 🛍️ E-Commerce Sales Analysis

An end-to-end sales analysis of a California-based e-commerce fashion retailer, built entirely in Microsoft Excel. The workbook covers transaction-level data, KPI summaries, trend analysis, and a geographic breakdown — all driven by PivotTables and structured reference sheets.

## 📁 File

FileDescriptionE-Commerce_Sales_Analysis.xlsxMain Excel workbook containing raw data, pivot tables, KPI dashboard, and analysis sheets

## 📊 Dataset Overview

AttributeValueTotal Orders2,400Total Items Sold11,997Total Revenue~$649,020Average Customer Rating4.0 / 5Average Delivery Time2.3 daysGeographyCalifornia (58+ counties)Time Period13 weeks (weekly breakdown)
Data Fields (per transaction)
TX ID · Product · Quantity · Unit Price · Amount · Order Date · Ship Date · Customer Gender · Order Mode · Rating · State · County · Days to Deliver · Week Number

## 🗂️ Workbook Structure

SheetContentsDataRaw transaction records (2,400 rows, one row per order)Sheet2KPI summary aggregates and 13-week trend pivotQuestions & KPIsBusiness questions driving the analysisDashboardVisual dashboard (charts and key metrics)Sheet4Revenue breakdown by order channel × gender (matrix)Sheet5Order quantity distribution + county-level geographic analysisSheet6Product performance by quantity and gender splitSheet7Shipping duration distribution + customer satisfaction ratings

## 🔍 Key Business Questions Answered

What is the sales trend over the last 13 weeks?
How do customers prefer to place orders? (App, Website, Instagram, Target.com, Partner App)
How many items do customers typically buy per order?
Which products are most popular?
What is the overall gender split of customers?
Where do customers live? (county-level heatmap data)
How long does order fulfillment take?
How satisfied are customers with their experience?


## 📈 Highlights from the Analysis

Top Products by Quantity Sold
ProductUnits SoldT-Shirts1,645Jeans1,546Sneakers1,186Tank Tops912Bikinis807
Order Channels (by Revenue Share)
ChannelShareWebsite~23.5%App~35.3%Target.com~18.3%Partner App~11.6%Instagram~11.3%
Customer Gender Split
GenderUnitsFemale6,272Male4,672Other317Unknown736
Shipping Performance

73% of orders delivered in 1–2 days
Maximum observed delivery: 14 days

## Customer Ratings Distribution

RatingOrders
⭐⭐⭐⭐⭐ (5)721
⭐⭐⭐⭐ (4)1,036
⭐⭐⭐ (3)495
⭐⭐ (2)127
⭐ (1)21

## 🛠️ Tools Used

Microsoft Excel — PivotTables, PivotCharts, conditional formatting, data validation
No external libraries or scripts required
