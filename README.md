# Sunrudh-Microgreens-Real-Dataset
Sunrudh Microgreens Real Dataset

Overview
This repository contains the **Sunrudh Microgreens Real Dataset**, a synthetic-yet-realistic dataset created to simulate real-world agricultural and sales data for a microgreen farming business — **Sunrudh Microgreens**.

The dataset intentionally includes **real-world messiness** such as nulls, duplicates, typos, inconsistent units, and mixed data types. It’s built to help analysts, data scientists, and Power BI developers practice **data cleaning, preprocessing, and visualization workflows**.

File Details
**File name:** `Sunrudh_Microgreens_RealData.xlsx`
**Rows:** 188 (including intentional duplicates)
**Columns:** 20

| Column          | Description                                                                    |
| --------------- | ------------------------------------------------------------------------------ |
| RecordID        | Unique identifier for each record                                              |
| Variety         | Type of microgreen (e.g., Pea, Radish, Basil) — includes typos and lowercasing |
| Family          | Botanical family of the variety                                                |
| SeedBatchID     | Unique seed batch identifier                                                   |
| SowingDate      | Date of sowing (in mixed formats)                                              |
| HarvestDate     | Date of harvest (in multiple formats)                                          |
| GrowthDays      | Growth duration (integer or text like “12 days”)                               |
| Temperature_C   | Recorded temperature (may include “C” or missing values)                       |
| Humidity_%      | Humidity readings (sometimes as percentages, e.g., “75%”)                      |
| LightHours      | Daily light exposure hours (some with “hrs”)                                   |
| SoilType        | Medium used, includes alternate spellings (“cocopeat”, “co co peat”)           |
| Compost         | Quantity applied (in grams or kilograms)                                       |
| Water           | Amount of water used (in ml or L)                                              |
| Yield           | Harvested yield (in grams or kilograms)                                        |
| GerminationRate | Percentage of successful germination (some as strings)                         |
| PestIncidence   | Type of pest issue, if any                                                     |
| pH              | Soil pH (some out-of-range values)                                             |
| EC_mS_cm        | Electrical conductivity                                                        |
| Price_per_kg    | Selling price (₹ format or numeric, includes per-100g errors)                  |
| Location        | Farm location within Bangalore                                                 |
| Notes           | General notes about the batch (“low germination”, “excellent germ”, etc.)      |

How to Use
This dataset is ideal for:
* Practicing **data cleaning and preprocessing** in Python or R
* Building **Power BI or Tableau dashboards**
* Exploring **data quality assessment and validation**
* Testing **ETL pipelines or data transformation scripts**
* Demonstrating **data storytelling and visualization projects**

Example Cleaning Challenges
1. Standardize date formats across columns
2. Convert all numeric fields (Temperature, Yield, Compost, Price) into consistent units
3. Identify and remove duplicates
4. Handle null or inconsistent entries in key columns
5. Map similar soil type variants into standardized categories
6. Detect and correct outliers (e.g., impossible pH or temperature values)

Project Context
This dataset was generated as part of the **Sunrudh Microgreens** analytics initiative, designed to simulate realistic farm production and sales data for internal Power BI visualization and data storytelling projects.

A clean reference version exists, and this “real” dataset mirrors it — but with **intentional chaos** to represent real-world data imperfections.


Creator:
**Rachel Roshani**
Data Analyst | MSc Big Data Analytics


📧 [Connect on LinkedIn](https://www.linkedin.com/in/rachelroshani)

License: 
This dataset is free to use for **educational and non-commercial purposes**. Attribution to **Sunrudh Microgreens Dataset by Rachel Roshani** is appreciated.

