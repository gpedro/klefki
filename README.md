# klefki

[![Known Vulnerabilities](https://snyk.io/test/github/rdiego26/klefki/badge.svg)](https://snyk.io/test/github/rdiego26/klefki)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a0a76a14056b48658641dc1a04aadaa5)](https://www.codacy.com/app/rdiego26/klefki?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rdiego26/klefki&amp;utm_campaign=Badge_Grade)
[![decov](https://codecov.io/gh/rdiego26/klefki/branch/master/graph/badge.svg)](https://codecov.io/gh/rdiego26/klefki)
[![NPM Version](https://img.shields.io/npm/v/express.svg?style=flat)](https://www.npmjs.org/package/klefki)
[![Build Status](https://travis-ci.org/rdiego26/klefki.svg?branch=master)](https://travis-ci.org/rdiego26/klefki)
[![Dependencies](https://david-dm.org/rdiego26/klefki.svg)](https://david-dm.org/rdiego26/klefki.svg)

Simple substitution cipher module.
It basically consists of substituting every plaintext character for a different ciphertext character. It differs from the [Caesar cipher](http://practicalcryptography.com/ciphers/caesar-cipher/) in that the cipher alphabet is not simply the alphabet shifted, it is completely jumbled.  
![Pokémon klefki](http://img.pokemondb.net/artwork/dream/klefki.png)


## Installation

  `npm install klefki --save`

## Usage

```
var klefki = require('klefki'),
      _word = 'abracadabra',
      _myKey = 'myKey',
      _cipher = '';
      _cipher = klefki.ciphers.simpleSubstitution.encrypt(_word, _myKey);
      klefki.ciphers.simpleSubstitution.decrypt(_cipher) === _word; // true
```

## Tests

  `npm test`


## Contributing

Don't be shy, send a Pull Request! Here is how:

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## References
-  [https://en.wikipedia.org/wiki/Substitution_cipher](https://en.wikipedia.org/wiki/Substitution_cipher)
-  [https://inventwithpython.com/hacking/chapter18.html](https://inventwithpython.com/hacking/chapter18.html)
