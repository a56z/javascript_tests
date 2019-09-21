#Phrase object (with palindrome detector)

This is a sample NPM module

The module can be used as follows:

```
$ npm install --global palindrome_a56z
$ vim test.js
let Phrase = require("palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```
