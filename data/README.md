# Data

The raw data is not included in this repository. Download it from Kaggle:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Put these 9 files in `data/raw/`:

| File | Rows |
|---|---|
| olist_customers_dataset.csv | 99,441 |
| olist_geolocation_dataset.csv | 1,000,163 |
| olist_orders_dataset.csv | 99,441 |
| olist_order_items_dataset.csv | 112,650 |
| olist_order_payments_dataset.csv | 103,886 |
| olist_order_reviews_dataset.csv | 99,224 |
| olist_products_dataset.csv | 32,951 |
| olist_sellers_dataset.csv | 3,095 |
| product_category_name_translation.csv | 71 |

Running the notebook creates `data/processed/cleaned_dataset.csv`: delivered orders with delivery delay, late flag, customer state, review score and payment summary.
