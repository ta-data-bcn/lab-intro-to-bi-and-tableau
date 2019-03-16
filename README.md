![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Introduction to Zeppelin

## Introduction

In this lab, we will practice loading data into Zeppelin, inspecting and modifying data types, and creating tabular views with metrics based on the information contained in the data set. We will be working with a liquor store sales data set hosted in our Ironhack database.

## Getting Started

To complete this lab, follow each of the steps below.

1. Open the dataset in your Zeppelin notebook.
5. Once the data set has been imported, change the data type for the Year field to string.
6. Create a new field called Quarter by binning the month field using a bin size of 4.
7. Create a new worksheet, drag the newly-created Quarter field into the Rows section, and drag the Number of Records measure to the center of the view. You will notice that the quarters are currently named labeled 0, 4, 8, 12. Rename them more intuitively by changing their names to Q1, Q2, Q3, and Q4 respectively.
8. Create new worksheets with tabular views for each of the following metrics.
    - Total Retail Sales by Year/Quarter (rows).
    - Average Retail Sales by Year/Quarter (rows).
    - Total Retail Sales by Year/Month (rows) and Item Type (columns).
    - Average Retail Sales by Year/Month (rows) and Item Type (columns).
    - Total Retail Transfers by Year/Quarter (rows).
    - Average Retail Transfers by Year/Quarter (rows).
    - Total Retail Transfers by Year/Month (rows) and Item Type (columns).
    - Average Retail Transfers by Year/Month (rows) and Item Type (columns).
    - Total Warehouse Sales by Year/Quarter (rows).
    - Average Warehouse Sales by Year/Quarter (rows).
    - Total Warehouse Sales by Year/Month (rows) and Item Type (columns).
    - Average Warehouse Sales by Year/Month (rows) and Item Type (columns).
9. Download your deliverable and copy it to your forked repository.

## Deliverables

- `main.json` file.

