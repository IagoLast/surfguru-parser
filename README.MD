SURFGURU-PARSER
---

A node.js scrapper to get surf forecast predictions from windguru.


## Installing 

    yarn add surfguru-parser


## Usage

```javascript
const surfguru = require('surfguru-parser');
const beachID = '48738'
surfguru(beachID)
    .then(predictions => console.log(predictions[0]))
    .catch(console.error);
```

## Compatibility

node.js >= `7.10.1`

## License

MIT