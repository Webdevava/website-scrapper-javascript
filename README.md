# Website-Scrapper

## Overview

This code is a Node.js script that uses the `website-scraper` package to scrape the content of a website and download it to a local directory. The scraped website URL is defined as `https://shopmrbeast.com`. 

## Dependencies

This code requires the following dependencies:

- Node.js
- website-scraper

## Installation

To install the required dependencies, run the following command in your terminal:

```
npm install website-scraper
```

## Usage

To use this code, save it to a file with a `.js` extension, and run it using Node.js in your terminal with the following command:

```
node file-name.js
```

When you run the script, it will download the entire content of the `https://shopmrbeast.com` website to a local directory called `./node-website`.

### Options

The script uses the following options:

- `urls`: An array of URLs to scrape. In this case, there is only one URL.
- `urlFilter`: A function that filters the URLs to scrape. This function checks if the URL starts with the `websiteUrl` variable defined as `https://shopmrbeast.com`.
- `recursive`: A Boolean that determines whether to scrape the website recursively.
- `maxDepth`: An integer that determines how many levels deep the recursive scraping should go.
- `prettifyUrls`: A Boolean that determines whether to prettify the URLs in the downloaded website content.
- `filenameGenerator`: A string that determines how the downloaded files should be named. In this case, the files are named by site structure.
- `directory`: A string that specifies the path to the directory where the downloaded content should be saved.

## Error Handling

If an error occurs during the scraping process, the script will log an error message to the console with the details of the error.
