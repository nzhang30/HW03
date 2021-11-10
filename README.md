# Nick - HW03: Ebay Web Scraping

---

## What the ebay-dl file does...

Uses python to scrape html code from eBay's website to collect data on products. 

1. Python file creates a url from the *search_term* that you input into the command line
2. Imports a JSON file and downloads the first 10 pages of search results for the *search_term*
3. Finds and pulls out those items from the downloaded pages, and creates a list contain data from the search

More Specifically...

The file creates the url from the search_term, downloads and runs the html and writes a JSON to the file. The data collected (scraped) in this project includes `name`, `price`, `items_sold`, `freereturns`, and `status`




## How to Run the ebay-dl File

Use the command below to run the ebay-dl file with any *search_term* of your choosing. For example, I searched for pants, bandannas, and hockey sticks. 

```
python3 ebay-dl.py 'search term'
```

## Command lines for my json files

For pants.json:
To search for 'pants' input: 
```
python3 ebay-dl.py 'pants'
```

To search for `hockey stick` input:
```
python3 ebay-dl.py 'hockey stick'
```

To search for `bandannas` input:
```
python3 ebay-dl.py 'bandanna'
```
---

**Parting Note:** Follow this link [here](https://github.com/mikeizbicki/cmc-csci040/tree/2021fall/hw_03) to read more about the project guidlines! Have a great day!
