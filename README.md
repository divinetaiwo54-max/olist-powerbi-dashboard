# Olist Sales & Customer Dashboard (Power BI)

Interactive Power BI dashboard built on ~100,000 orders from the Brazilian marketplace Olist.

## Overview
![Overview](overview.png)

## Customers & Delivery
![Customers & Delivery](customers_delivery.png)

## Key insights
- R$15.84M revenue from 99K orders and 96K customers.
- Daily revenue shows a sharp spike on Black Friday (Nov 2017).
- 8.1% of orders arrive late, with northern states like AL and MA hit hardest.
- Late orders average 2.6 stars vs 4.3 for on-time orders.

## What I built
- Cleaned and merged data in Power Query (English category names, late-delivery flag)
- Star schema with 8 related tables and a custom date table
- DAX measures: revenue, orders, customers, average order value, late delivery %, average review score

## Tools
Power BI · Power Query · DAX

## Data
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle)
