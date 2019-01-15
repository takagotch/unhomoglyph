### unhomoglyph
---
https://github.com/nodeca/unhomoglyph

```
npm install unhomoglyph --save
npm run update
```

```js
const unhomoglyph = require('unhomoglyph');
console.log(unhomoglyph('AAAAAA'));
console.log(unhomoglyph('m'));

const username1 = 'm';
const username2 = 'rn';
if(unhomoglyph(username1) === unhomoglyph(username2)){
  console.log(`"${username1}" and "${username2} look similar"`);
}
```

```
```


