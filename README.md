# SeleniumRestAssuredTestng
Is a java project that do an assertion between 2 result of test executions

Important notes if you want to execute in windows:

- I was working in a MAC for that reason you can see this chromedriver in the folder, if you want to execute in Windows download an chromedriver for windows (.exe). Use the version 11 not the 12.
		https://chromedriver.chromium.org/downloads

- Change the name of the ChromeDriver in TestSearch.java / setUp() method / System.setProperty:
			System.setProperty("webdriver.chrome.driver", "drivers/chromedriver");

For execution:

- Open the testSuite.xml

- Change the parameters for the web search:
   Country : for the search in google

- Change the parameters for endpoint search:
   lat: Latitude 
   lon: longitude
   apik: Apikey for the service

Technologies:

- Selenium
- PageObject
- RestAssured
- TestNg