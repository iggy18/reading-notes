# web scraping

- Web scraping is a technique to automatically access and extract large amounts of information from a website, which can save a huge amount of time and effort.

- start by importing ...
- import requests
- import urllib.request
- import time
- from bs4 import BeautifulSoup

- then setup a variable to store the website URL and access the site with the request library
- `URL = wwww.example.com`
-`response = requests.get(url)`

- run the response through beautiful soup
-`soup = BeautifulSoup(response.text, “html.parser”)`

- use the `.findAll` to locate all tags you are looking for 
- `soup.findAll('a')`

- extract the actual link that we want
- `one_a_tag = soup.findAll(‘a’)[38]`
- `link = one_a_tag[‘href’]`

- use urllib to request library to download file path to computer. it wants two perameters file path and file name.
- download_url = 'http://web.mta.info/developers/'+ link
urllib.request.urlretrieve(download_url,'./'+link[link.find('/turnstile_')+1:])

- lastly, you'll want to put a timer on your program so you don't get blocked by the site.
- `time.sleep(1)`