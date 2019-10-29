# smashtest
[Smashtest](https://smashtest.io) sample project

## setup

Requires:  
- [NodeJS](https://nodejs.org/) installed.  
- Webdrivers: download the desired webdrivers (the tests in this example call for Chrome and Firefox) and include the executables in your PATH or copy them to `/tests`.  
  - [Chrome](http://chromedriver.chromium.org/downloads)  
  - [Firefox](https://github.com/mozilla/geckodriver/releases)  
  - [Edge](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/)  
  - [IE](https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver)  
- For chromedriver to behave well with parallel and typing, make sure you follow the [setup](https://smashtest.io/getting-started/setup) to set the `SELENIUM_SERVER_JAR` environment variable.  

## run

`npm install` then `npm test`  

## report

`npm run report`  
