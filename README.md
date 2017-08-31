# Installing and Running Node
You should only have to install Homebrew and Node once in your time at Prime. Follow the instructions below.

## Installing Homebrew and Node.js (one-time)
1. [Install Homebrew](http://brew.sh/). This will be done on the command line (Terminal). 
2. Once Homebrew is installed, run the command: `brew install node`
3. When this is complete, run this at your Terminal: `node --version` If you see a number, you are good to go.


## Install the dependencies for the assignemnt.

Navigate into the assignment directory. eg: `prework-week-2-assignment`.

npm stands for "node package manager"
Then run the command `npm install` in the terminal.  This will install all the needed packages for the tests to work in that directory. 


## Run the tests
use the command `npm test` in the assignment directory

The tests will show up in the terminal. The terminal will focus on the tests that fail. They will probably have some text in red. The text will be very similiar to the test on the Testing App. 


# Reading the Tests

Each time you run `npm test`, the tests will run. 

## Syntax Error
Here's screenshot of what the tests show if there is a syntax error that is preventing the tests from running. In this case, it gives a hint: `assignment/3_scope.js:18`. So I'll start looking for that error on line 18 of `3_scope.js`.

![syntax error](syntaxError.png)

## Some Passing, Some Failing
Some tests passing, some tests failing. It says it ran all the tests and 2 of them failed: `Executed 4 of 4 (2 FAILED)`

In red, it describes the tests that failed. `basemode theDoubler logs the correct responses based on type FAILED`

![two tests passing, two failing](twoPassTwoFail.png)

## All Tests Passing
Finally, here's a screenshot of all the tests passing. `Executed 4 of 4 SUCCESS `!
![all tests passing!](allTestsPassing.png)
