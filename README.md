# Scraping using Scrapy Python

## Target
<https://books.toscrape.com/>

## What data we extract ?
We extract all information of the books in the web.

## format of the json data
 {
    "name": "title",
    "price": "price in £ poundsterling",
    "url": "link to the book"
  }

## Scrapy info
{'downloader/request_bytes': 15362,
 'downloader/request_count': 51,
 'downloader/request_method_count/GET': 51,
 'downloader/response_bytes': 277586,
 'downloader/response_count': 51,
 'downloader/response_status_count/200': 50,
 'downloader/response_status_count/404': 1,
 'dupefilter/filtered': 931,
 'elapsed_time_seconds': 28.63644,
 'feedexport/success_count/FileFeedStorage': 1,
 'finish_reason': 'finished',
 'finish_time': datetime.datetime(2024, 2, 2, 9, 57, 13, 744756, tzinfo=datetime.timezone.utc),
 'httpcompression/response_bytes': 2543114,
 'httpcompression/response_count': 51,
 'item_scraped_count': 1000,
 'log_count/DEBUG': 1055,
 'log_count/INFO': 11,
 'memusage/max': 57856000,
 'memusage/startup': 57856000,
 'request_depth_max': 49,
 'response_received_count': 51,
 'robotstxt/request_count': 1,
 'robotstxt/response_count': 1,
 'robotstxt/response_status_count/404': 1,
 'scheduler/dequeued': 50,
 'scheduler/dequeued/memory': 50,
 'scheduler/enqueued': 50,
 'scheduler/enqueued/memory': 50,
 'start_time': datetime.datetime(2024, 2, 2, 9, 56, 45, 108316, tzinfo=datetime.timezone.utc)}
