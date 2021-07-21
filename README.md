
First run ```npm install tomatoShort``` to install the tomatoShort package to your system.

```javascript
var TmSh = require('tinyurl');

TmSh.shorten('http://google.com', function(res, err) {
  if (err)
    console.log(err)
	console.log(res);
});

// Shorten with Alias Example
const data = { 'url': 'https://google.com', 'alias': 'custom-alias-for-google' }

TmSh.shortenWithAlias(data, function(res, err) {
  if (err)
    console.log(err)
	console.log(res); //Returns a shorter version of http://google.com - http://tinyurl.com/2tx
});

    console.log(err);
  }
);
```

