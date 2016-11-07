
# slug-generator

[![npm-version]][npm] [![travis-ci]][travis] [![coveralls-status]][coveralls]

This is vanilla javascript port of [node-slug](https://github.com/dodo/node-slug) so all credits goes to [dodo](https://github.com/dodo) and [simov](https://github.com/simov/slugify.git).

This script convert cyrilic to latin URI slug. 

```js
var slugify = require('slug-generator')

// add string to a function to create slug 
slugify('this is a string') // returns this-is-a-string

// if you want to change default separator(-) add 2nd paramenter to function 
slugify('this is a string', '_') //returns this_is_a_string
```
