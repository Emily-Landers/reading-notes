# Web Scraping

**Web scraping is a technique to automatically access and extract large amounts of information from a website**

- Web scraping a web page involves fetching it and extracting from it. Fetching is the downloading of a page (which a browser does when a user views a page). Therefore, web crawling is a main component of web scraping, to fetch pages for later processing.
- Once fetched, then extraction can take place. The content of a page may be parsed, searched, reformatted, its data copied into a spreadsheet or loaded into a database.
- If a crawler performs multiple requests per second and downloads large files, an under-powered server would have a hard time keeping up with requests from multiple crawlers.
- There are methods that some websites use to prevent web scraping, such as detecting and disallowing bots from crawling (viewing) their pages. In response, there are web scraping systems that rely on using techniques in DOM parsing, computer vision and natural language processing to simulate human browsing to enable gathering web page content for offline parsing.
- Web scraping methods include:
    - Human copy-and-paste
    - Text pattern matching
    - HTTP programming
    - HTML parsing
    - DOM parsing
    - Vertical aggregation
    - Semantic annotation recognizing
    - Computer vision web-page analysis
- Read through the website you intend to scrapes Terms and Conditions to understand how you can legally use the data. Most sites prohibit you from using the data for commercial purposes.
- Make sure you are not downloading data at too rapid a rate because this may break the website. You may potentially be blocked from the site as well.
- The first thing that we need to do is to figure out where we can locate the links to the files we want to download inside the multiple levels of HTML tags.
    - we can do this by using the "inspect" function
- import the following:

```
import requests
import urllib.request
import time
from bs4 import BeautifulSoup
```

- Set the url

```
url = 'http://web.mta.info/developers/turnstile.html'
response = requests.get(url)
```
- We should include this line of code so that we can pause our code for a second so that we are not spamming the website with requests. This helps us avoid getting flagged as a spammer.

```time.sleep(1)```

- Make your spider look real, by mimicking human actions. Put some random programmatic sleep calls in between requests, add some delays after crawling a small number of pages and choose the lowest number of concurrent requests possible. Ideally, put a delay of 10-20 seconds between clicks and not put much load on the website, treating the website nice.
- Use auto throttling mechanisms which will automatically throttle the crawling speed based on the load on both the spider and the website that you are crawling.
- send requests from a proxy machine, the target website will not know where the original IP is from, making the detection harder.
- Create a pool of IPs that you can use and use random ones for each request. Along with this, you have to spread a handful of requests across multiple IPs.
- There are several methods that can change your outgoing IP:

    - TOR
    - VPNs
    - Free Proxies
    - Shared Proxies
    - Private Proxies
    - Data Center Proxies
    - Residential Proxies (last resort)
- Do not send cookies unless your scraper depends on Cookies for functionality.
- When following links always take care that the link has proper visibility with no nofollow tag. Some honeypot links to detect spiders will have the CSS style display:none or will be color disguised to blend in with the page’s background color.
- Avoid scraping data behind a login
- Use Captcha Solving Services

## Resources

- https://towardsdatascience.com/how-to-web-scrape-with-python-in-4-minutes-bc49186a8460 
- https://en.wikipedia.org/wiki/Web_scraping 
- https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/ 