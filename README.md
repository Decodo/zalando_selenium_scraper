<p align="center">
<a href="https://dashboard.decodo.com/?page=residential-proxies&utm_source=socialorganic&utm_medium=social&utm_campaign=resi_trial_GITHUB"><img src="https://github.com/user-attachments/assets/60bb48bd-8dcc-48b2-82c9-a218e1e4449c"></a>
</p>


[![](https://dcbadge.vercel.app/api/server/Ja8dqKgvbZ)](https://discord.gg/Ja8dqKgvbZ)
## Dependencies

```
BeautifulSoup
webdriver_manager
selenium
extension >> extension.py
```

## Authentication

You can create, edit, and delete proxy users in our Dashboard > Residential > Proxy setup page.

## Zalando Selenium Scraper

This code is a Python script that uses the Selenium and BeautifulSoup libraries to scrape product information from Zalando.

The script uses the Chrome web browser, controlled by the Selenium library, to navigate to the website and retrieve its source code. The source code is then parsed using BeautifulSoup to extract specific information about each product on the page.

In order to use a proxy, the code uses the "webdriver_manager" and "extension" libraries to install the Chrome driver and configure the Chrome browser to use a proxy server. The credentials for the proxy server, including username, password, endpoint, and port, are passed as arguments to the "proxies" function in the "extension" library (extension.py).

The script then uses BeautifulSoup to search the page source for specific tags containing the product information. The product information is then stored in a dictionary and added to a list "data".

Finally, the script saves the "data" list to a JSON file named "data.json".

