# Libur

[![Build Status](https://travis-ci.org/muhtarudinsiregar/libur.svg?branch=master)](https://travis-ci.org/muhtarudinsiregar/libur)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/cb4ba14a1e9a497986cba8ac24daf5db)](https://www.codacy.com/app/muhtarudinsiregar/libur?utm_source=github.com&utm_medium=referral&utm_content=muhtarudinsiregar/libur&utm_campaign=badger)

Package untuk list hari libur nasional indonesia

### installation
```javascript
npm install libur

or

yarn add libur
```

## Usage
```javascript
const Libur = require('libur');
const libur = new Libur();

console.log(libur.getYears()); // return list of years [2013, 2014, ...]

// params int years
// return array list of holiday in year

console.log(libur.getDataByYear(2013));
```

### Test
```javascript
npm test
```

### Datasource
http://www.liburnasional.com/
