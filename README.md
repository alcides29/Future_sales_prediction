# Future Sales Prediction

This challenge serves as final project for the "How to win a data science competition" Coursera course.


### Description
We Will work with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company. 

### Objective

- To predict total sales for every product and store in the next month.
- To create a robust model that can handle such situations is part of the challenge.

You are provided with daily historical sales data. Note that the list of shops and products slightly changes every month.

### File descriptions
* **sales_train.csv** - the training set. Daily historical data from January 2013 to October 2015.
* **test.csv** - the test set. You need to forecast the sales for these shops and products for November 2015.
* **sample_submission.csv** - a sample submission file in the correct format.
* **items.csv** - supplemental information about the items/products.
* **item_categories.csv** - supplemental information about the items categories.
* **shops.csv** - supplemental information about the shops.

### Data descriptions

| Name | Data Type | Description |
| ---- | --------- |-------------|
|	ID | int	 | An Id that represents a (Shop, Item) tuple within the test set |
|	shop_id | int   | Unique identifier of a shop	|
|	item_id | int   | Unique identifier of a product |
|	item_category_id | int	 | Unique identifier of item category |
|	item_cnt_day | float	 | Number of products sold. You are predicting a monthly amount of this measure |
|	item_price | float | Current price of an item |
|	date | object 	 | Date in format dd/mm/yyyy |
|	date_block_num | int | A consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33 |
|	item_name | object	 | name of item |
|   shop_name | object  | name of shop |
|   item_category_name | object   | name of item category |


The datasets can be found on the dataset folder. The *sales_train.csv* can be found [here](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data) from Kaggle.

For more information, you can visit the [kaggle competition](https://www.kaggle.com/c/competitive-data-science-predict-future-sales) website.
