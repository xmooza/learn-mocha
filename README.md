Learn Mocha [![Build Status](https://api.travis-ci.org/ismail-syed/learn-mocha.png?branch=master)](https://travis-ci.org/ismail-syed/learn-mocha)
===========

[Workshop slides](https://docs.google.com/presentation/d/1iasIefDNppqvO2VTInE5lDU8Nt0u4yWh3FzWY3PcExY/edit?usp=sharing)

[codeanywhere: cloud based development environment](https://codeanywhere.com/)

### Setup dev environment
```
npm install
```

## Dev environment setup

### Fork the project
* Click the `Fork` on the top right of the project homepage
* Now you have your own copy of the project under your Github Account!

### Create a codeanywhere dev environment
* Create a [codeanywhere](https://codeanywhere.com/) account
* Login with GitHub
* Verify your account. An email should be sent to you email linked with GitHub
* `File` > `New Connection` > `Git from URL`
* Paste in `https://github.com/<your-github-username>/learn-mocha.git`
* `Name`: doesn't matter
* Search Stack: `Node.js - Ubuntu 14.04`
* Create!
* Wait a few minutes
* You should see your projects files on the left

### Open terminal:
* Right click on your root folder project name
* Click `SSH Terminal
* You should see a big terminal window
* Type in `npm install` -> This will pull in all you Node.js dependencies
* Run your tests: `npm run test`

You should see broken tests cases. Now you'll need to explore around the project files and fix the tests cases.
Makes some changes, then run your tests.

*NOTE*: See `Git workflow` section below

# Running tests
```
npm run test
```

## Git workflow
* Create and checkout into a new branch `git checkout -b <your-branch-name>`
* Make changes locally
* `git status` to see the state of your changes
* `git commit -am "Fixing the build"` to commit your changes
* `git log` to see your
* `git push origin <your-branch-name>`
