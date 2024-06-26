# Web Scraping - for Sephora & Strawberrynet
Web crawler and demo tools 

## Table of Content
* [Setup](#Setup)
* [Features](#Features)
* [Example](#Example)
* [Technologies](#Technologies)
* [Website Related](#Website-Related)

## Setup
To Run this project, install it locally Or in Virtual Environment as your refercence, using Python Package Managers (pip) :

```
pip install -r requirements.txt
```

## Features
* ETL pipeline set-up
* Data Scraping for Strawberrynet & Sephora
* Product detail URL Store in directory in your control
* Generate Csv file for different product detail for each sub-categories
* New data comparison with old data

## Example

```
# whole process of strawberrynet data scraping
strawberry_product_scraping(url)

# clean all the scraped data and generate a csv file 
st_data_clean(dir='./st_csv_folder')

# return a list as [new_product_dataframe , new_data_dataframe]
st_new_item_checker()
```

## Technologies

* Pandas version : 2.2.1
* selenium version : 4.18.1

*more in requirements.txt*

# Website Related
* [Sephora](https://www.sephora.hk/)
* [Strawberrynet](https://www.strawberrynet.com/en-hk)
