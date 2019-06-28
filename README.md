# Neos-ui testing distribution

This repository provides a neos-cms distribution for testing the neos-ui.
The neos-ui is using [testcafe](https://github.com/DevExpress/testcafe) for acceptance testing and needs fixure data
for the test cases.

The distribution is used for the circle ci pipelin and you can also use it for your
local environment. The distribution is currently based on neos 3.3 because the lowest maintained
branch for the Ui is 2.x and is for neos 3.3.

## Installation and usage

1. Clone distribution

```
git clone git@github.com:neos/neos-ui-testing-distribution.git
```

2. Run composer install with sources:

```
cd neos-ui-testing-distribution
composer install --prefer-source
```

3. Start the neos instance

```
./flow server:run
```
