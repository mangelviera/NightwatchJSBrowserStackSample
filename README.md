Handling and use guide:

    - npm install
    - To run test locally with Selenium:
        - java -jar selenium-server-standalone-2.53.0.jar
        - ./node_modules/.bin/nightwatch
    - To run test using BrowserStack:
        - ./node_modules/.bin/nightwatch -c ./browserstack -e firefox-windowsXP,chrome-elcapitan
