Notes
-----
1. Monster.com is using client side rendering so we need to load the html in a browser
using the ChromeWebdriver and then parse it after a delay.

How to use venv ** Need this to run code
--------------------
1. Activate in macOS 
  In project directory  `source env/bin/activate`

2. How to deactivate in macOS
    In project directory  `deactivate`

How to install dependencies
-----------------------
Once venv is activated
`pip install -r install_requirements.txt`

How to add dependencies to install file
--------------------------------------------
`pip freeze > install_requirements.txt`


Guide
https://sadesmith.com/2018/06/15/blog/scraping-client-side-rendered-data-with-python-and-selenium

ChromeWebdriver
http://chromedriver.chromium.org/downloads