# Delete all Woocommerce orders
Delete all your Woocommerce orders with this script. Use at own risk

## I just want the SQL-queries
Here you go!
```
DELETE FROM wp_woocommerce_order_itemmeta
DELETE FROM wp_woocommerce_order_items
DELETE FROM wp_posts WHERE post_type = 'shop_order'
```
