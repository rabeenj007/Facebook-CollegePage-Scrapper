# facebook-college-page-scrapper
Using selenium webautomation tool, various informations of a facebook page is scrapped and stored in a csv file.

# How to execute

1.Clone the repo and install all the dependencies from requirments.txt
    
    pip install -r requirements.txt
    
2.Download and install latest version of chrome browser.

3.Download latest chromedriver(in my case 2.45)

4.Add chromedriver to the PATH by copying the chromedriver.exe file in /usr/bin or /usr/local/bin or change the executable path like:
    
    browser=webdriver.Chrome(executable_path='pathofchromedriver')

5.For headless option in Chrome
                   
    option = webdriver.ChromeOptions()
    option.add_argument("--headless")
    browser = webdriver.Chrome(executable_path='pathofchromedriver',options=option)


5.Open terminal on the location of the directory and run init.py

    python init.py
