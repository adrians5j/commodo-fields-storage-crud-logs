# commodo-fields-storage-crud-logs
[![Build Status](https://travis-ci.org/doitadrian/commodo-fields-storage-crud-logs.svg?branch=master)](https://travis-ci.org/doitadrian/commodo-fields-storage-crud-logs)
[![Coverage Status](https://coveralls.io/repos/github/doitadrian/commodo-fields-storage-crud-logs/badge.svg?branch=master)](https://coveralls.io/github/doitadrian/commodo-fields-storage-crud-logs?branch=master)
[![](https://img.shields.io/npm/dw/commodo-fields-storage-crud-logs.svg)](https://www.npmjs.com/package/commodo-fields-storage-crud-logs) 
[![](https://img.shields.io/npm/v/commodo-fields-storage-crud-logs.svg)](https://www.npmjs.com/package/commodo-fields-storage-crud-logs)
![](https://img.shields.io/npm/types/commodo-fields-storage-crud-logs.svg)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  
A object field for Commodo composeable models. 

## Install
```
npm install --save commodo-fields-storage-crud-logs
```

Or if you prefer yarn: 
```
yarn add commodo-fields-storage-crud-logs
```

## Quick Example:
 
```javascript
import { compose } from "ramda";
import { withFields, string } from "@commodo/fields";
import { object } from "commodo-fields-storage-crud-logs";

const Company = compose(
  withFields({
    name: string(),
    createdOn: object()
  })
)(function() {});
```

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars0.githubusercontent.com/u/5121148?v=4" width="100px;"/><br /><sub><b>Adrian Smijulj</b></sub>](https://github.com/doitadrian)<br />[💻](https://github.com/doitadrian/commodo-fields-storage-crud-logs/commits?author=doitadrian "Code") [📖](https://github.com/doitadrian/commodo-fields-storage-crud-logs/commits?author=doitadrian "Documentation") [💡](#example-doitadrian "Examples") [👀](#review-doitadrian "Reviewed Pull Requests") [⚠️](https://github.com/doitadrian/commodo-fields-storage-crud-logs/commits?author=doitadrian "Tests") |
| :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!
