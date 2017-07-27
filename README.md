[![forthebadge](http://forthebadge.com/images/badges/built-by-codebabes.svg)](https://jaque.me/)

[![Stories in Progress](https://img.shields.io/waffle/label/malpercio/skipper-gclouds/in%20progress.svg?style=flat)](https://waffle.io/malpercio/skipper-gclouds)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/c988b9a0675b43ff964e76168b9975c3)](https://www.codacy.com/app/danielglezespinoza/skipper-gclouds?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=malpercio/skipper-gclouds&amp;utm_campaign=Badge_Grade)
[![bitHound Code](https://www.bithound.io/github/malpercio/skipper-gclouds/badges/code.svg)](https://www.bithound.io/github/malpercio/skipper-gclouds)
[![bitHound Dependencies](https://www.bithound.io/github/malpercio/skipper-gclouds/badges/dependencies.svg)](https://www.bithound.io/github/malpercio/skipper-gclouds/master/dependencies/npm)
[![dependencies Status](https://david-dm.org/malpercio/skipper-gclouds/status.svg)](https://david-dm.org/malpercio/skipper-gclouds)
[![DevDependencies](https://david-dm.org/malpercio/skipper-gclouds/dev-status.svg)](https://david-dm.org/malpercio/skipper-gclouds)
[![npm version](https://badge.fury.io/js/skipper-gclouds.svg)](https://badge.fury.io/js/skipper-gclouds)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/malpercio/skipper-gclouds/master/LICENSE)


skipper-gclouds
===========

A skipper adapter to allow uploading files to Google Cloud Storage


## Usage

```js
req.file('avatar').upload({
  // ...any other options here...
  adapter: require('skipper-gclouds'),
  projectId: 'YOUR_PROJECTID',
  keyFilename: 'YOUR_KEYFILENAME_PATH',
  email: 'YOUR_GCS_EMAIL',
  scopes: ['YOUR_SCOPES'],
  bucket: 'YOUR_GCS_BUCKET',
  //Are files uplodaded public?
  public: true,
}, ...);
```

## Special Thanks

Forked from [skipper-gcs](https://github.com/onlinemad/skipper-gcs) by **Ian Wu** <onlinemad@gmail.com>

## License
[MIT](./LICENSE)


[![NPM](https://nodei.co/npm/skipper-gclouds.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/skipper-gclouds/)
