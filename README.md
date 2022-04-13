# Web-Scraping - Amazon
## Overview
* This project is a web scraper written in Python language.
* Its purpose is to read Amazon Product URLs from given csv file and scrape data.

## Features
* Scarpe the following details from the page.
  1. Product Title
  2. Product Image URL
  3. Price of the Product
  4. Product Details
* If any URL throws Error 404 then print the {URL} not available and skip that URL.
* Print Time Taken After Scraping every 100 URLs
* Dump the extracted data into a JSON file.
* Store the same data in MySQL database.

## Requirements
* [Python](https://www.python.org/downloads/)
* [VS Code (Or Any Other IDE)](https://code.visualstudio.com/download)
* [XAMPP](https://www.apachefriends.org/download.html)

## Usage
* Clone the repository and open with VS Code (or any other suitable IDE).
* Install Dependencies - 

  ```pip install beautifulsoup4```
  
  ```pip install requests```
  
  ```pip install csv```
  
  ```pip install mysql```
 
* Create a database named "amazon_scrape" with table named "scraped_data".
* Run the Script with command 

  ```python script.py```
  
## Screenshots
### Amazon Product
![Amazon Product](https://github.com/aka-nikko/Web_Scraping-Amazon/blob/master/screenshots/amazon.png)

### Output
![Output](https://github.com/aka-nikko/Web_Scraping-Amazon/blob/master/screenshots/output.png)

### Json File
![Json File](https://github.com/aka-nikko/Web_Scraping-Amazon/blob/master/screenshots/json.png)


### MySQL Database
![MySQL Database](https://github.com/aka-nikko/Web_Scraping-Amazon/blob/master/screenshots/mysql.png)
