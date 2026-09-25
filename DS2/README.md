# DS2 – Olist Processed Dataset

## Purpose

This folder contains the project-specific processed data from the Olist Brazilian E-Commerce dataset.

The Olist dataset is used for:
- Lead-time analysis
- Delivery analysis
- Seller performance analysis

## Processed Files

### orders_processed.csv
Contains order status and order/delivery timestamps required for lead-time and delivery analysis.

### order_items_processed.csv
Contains order items, products, sellers, prices and freight values required for seller and order analysis.

### sellers_processed.csv
Contains seller ID and seller location information required for seller performance analysis.

## Cleaning Performed

- Selected only the columns required for the project.
- Removed leading and trailing spaces from text values.
- Converted empty text values to missing values.
- Converted date/time columns into datetime format.
- Converted numeric columns into numeric format.
- Removed exact duplicate rows.
- Checked relationships between orders, order items and sellers.

## Source

Olist Brazilian E-Commerce Dataset:

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
