# Sleep
Function `sleep` for JavaScript. 
>sleep(seconds) -> Promise
## Installation

    npm i webgirlkristina-sleep

## Usage

```js
const sleep = require('webgirlkristina-sleep');
const test = async () => {
	console.log('text1');
	await sleep(2); //sleep for 2 seconds
	console.log('text2');
};
test();
```