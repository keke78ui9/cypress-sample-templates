+ good for end to end test for web application
+ use javascript to write test

# setup cypress
```
npm install --save-dev cypress
```

# writing test

# running test
```
// run cypress in browser
"cy": "cypress open",
// run cypress in command, create video for each test
"cy:cli": "cypress run --headless",
"cy:report": "cypress run --reporter junit --reporter-options mochaFile=junit.xml,toConsole=true"
```

# debug test
```
```

# issues
+ safari support
    + https://github.com/cypress-io/cypress/issues/6422


# cypress cli
https://docs.cypress.io/guides/guides/command-line.html#cypress-run
# cypress configuration
https://docs.cypress.io/guides/references/configuration.html#Folders-Files
# cypress samples

# browser
    + chromium
    + edge
    + electron
    + firefox

# OS
    + macOS
    + Linux
    + Windows    