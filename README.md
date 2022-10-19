# WDIO-BS-sample

## Setup
* Clone the repo <br>

`git clone https://github.com/SachinMNair/WDIO-local-sample.git`

* Install dependencies <br>

`npm install`

* Export credentials

`export BROWSERSTACK_USERNAME=<browserstack-username>` <br>
`export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>`

## Running your tests
- Run the test <br>

`npm run wdio`

## Points to be checked.

- Check whether the website is loading or not before the session ends <br>
- If the website loads, check the time it took to load <br>
- Check the local console logs to see if there is any timeout error received
