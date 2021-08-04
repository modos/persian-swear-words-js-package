[![GitHub issues](https://img.shields.io/github/issues/modos/persian-swear-words-js-package)](https://github.com/modos/persian-swear-words-js-package/issues)
[![GitHub forks](https://img.shields.io/github/forks/modos/persian-swear-words-js-package)](https://github.com/modos/persian-swear-words-js-package/network)
[![GitHub stars](https://img.shields.io/github/stars/modos/persian-swear-words-js-package)](https://github.com/modos/persian-swear-words-js-package/stargazers)
[![GitHub license](https://img.shields.io/github/license/modos/persian-swear-words-js-package)](https://github.com/modos/persian-swear-words-js-package/blob/main/LICENSE)
[![Twitter](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fmodos%2Fpersian-swear-words-js-package)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fmodos%2Fpersian-swear-words-js-package)

<h1>a javascript package for filter persian swear words</h1> <br>
Thanks to : https://github.com/amirshnll <br>

Link on npm : https://www.npmjs.com/package/@modos.m98/persian-swear-words

## Install

```
npm i @modos.m98/persian-swear-words
```

## Import

```
const swear = require("@modos.m98/persian-swear-words")
```

## Usage
<a href="https://gist.github.com/modos/fb450a19d9da1c6d6cfbc2462b8687e5">Gist</a>

<br>

### 🔸 Check a string contains bad word
<br>

```
let text = 'علی خر است'
swear.hasSwear(text) /// returns true
```

### 🔸 Check a word is bad or not
<br>

```
let text = 'کسکش'
swear.is_bad(text) /// returns true

let text2 = 'سلام'
swear.is_bad(text2) /// returns false
```

### 🔸 Add word to list
<br>

```
let text = 'تخم'
swear.add_word(text)
```

### 🔸 Remove word from list
<br>

```
let text = 'تخم'
swear.remove_word(text)
```