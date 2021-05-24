# Google Search Scraper
Lets you scrape Google Search results.
Simulates the behaviour of a web browser, by sending a GET request that contains the User-Agent header, and consent cookies.
```python
from google_search import google_search

req = google_search()
req.search("cat")
req.write_2_file()
```
The code above shows the module being used to search google with the query `cat`, it then writes the returned HTML to a file.
Alternatively you can store the HTML in a variable.
```python
from google_search import google_search

req = google_search()
req.search("cat")
html = req.html
```
