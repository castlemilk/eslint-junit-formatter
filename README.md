# ESlint JUnit formatter

Produces JUnit XML output which will work with bamboo and bitbucket pipelines. Solves the following problems:

* non-empty test output
* eslint warnings can be supressed from final report output
* shows passing tests in report

## Usage

`eslint checks -f node_modules/eslint-junit-formatter/reporter.js