## Step by Step download

1) Download NodeJs installer as we need to use npm to install protractor
https://nodejs.org/en/download/

**What is npm?
npm makes it easy for JavaScript developers to share and reuse code, and makes it easy to update the code that you’re sharing, so you can build amazing things.

2) Open CMD and use npm command to install two command line tools, protractor and webdriver-manager. Try running protractor --version to make sure it's working.

  npm install -g protractor

3)The webdriver-manager is a helper tool to easily get an instance of a Selenium Server running. Use it to download the necessary binaries with:
 a) webdriver-manager update
 b) webdriver-manager start
    This will start up a Selenium Server and will output a bunch of info logs. Your Protractor test will send requests to this server to control a local browser. You can see information about the status of the server at
    http://localhost:4444/wd/hub.
