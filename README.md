# ScrapyTagram
This is a Scrapy project to scrape images URLS from an Instagram profile,

This project is only meant for educational purposes.
I meant to create this project as a way to learn to use Scrapy using XPath tags, as the Scrapy tutorial uses CSS selectors.


## Extracted data

This project extracts URLs, combined with the respective author names and tags.
The extracted data looks like this sample:

    {
        'link': '',
        'description': ''
    }


## Spiders

This project contains one spider and you can list them using the `list`
command:

    $ scrapy list
    scrapytagram

## Running the spiders

You can run a spider using the `scrapy crawl` command, such as:

    $ scrapy crawl scrapytagram

If you want to save the scraped data to a file, you can pass the `-o` option:
    
    $ scrapy crawl scrapytagram -o urls.json
