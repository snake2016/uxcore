English | [中文](./README_CN.md)

# [UXCore](http://uxco.re/)

[![npm version](https://img.shields.io/npm/v/uxcore.svg?style=flat-square)](https://www.npmjs.com/package/uxcore) [![Dependency Status](https://img.shields.io/david/uxcore/uxcore.svg?label=deps&style=flat-square)](https://david-dm.org/uxcore/uxcore) [![devDependency Status](https://img.shields.io/david/dev/uxcore/uxcore.svg?label=devDeps&style=flat-square)](https://david-dm.org/uxcore/uxcore#info=devDependencies)

UXCore is a set of [React](http://facebook.github.io/react/) Components that is designed for enterprise-class pc backend application.

* **Rich Library:** more than 50 high quality React Components available

* **Focus on Enterprise-class App:** Powerful but easy-to-use Form and Table.

* **Well Designed UI:**  designed for enterprise-class app to make work easy and happy.


Check out our [documentation site](http://uxco.re/) for live examples. 

Before posting an issue, please read the [CHANGELOG](https://github.com/uxcore/uxcore/releases) and the README and the documentation to check the recently updated.


## Installation

```sh
npm install uxcore --save
```

## Usage

### import js

```jsx
import { Button } from 'uxcore';
ReactDOM.render(<Button />, mountNode);
```

### import js as required

* use [babel-plugin-import](https://github.com/ant-design/babel-plugin-import) (recommanded)

  ```js
  // .babelrc or babel-loader option
  {
    "plugins": [
      ["import", { libraryName: "uxcore", camel2DashComponentName: false }]
    ]
  }
  ```


* or, import manually

  ```js
  import Button from 'uxcore/lib/Button';
  ```

### import style package

```less
@import '~uxcore/assets/iconfont.css';
@import '~uxcore/assets/orange.css';
```


## Browser Support

Mainstream browsers and Internet Explorer 9+.

## Contribute

Yes please! See the [CONTRIBUTING](https://github.com/uxcore/uxcore/blob/master/CONTRIBUTING.md) for details.

## License

This project is licensed under the terms of the [MIT license](https://github.com/uxcore/uxcore/blob/master/LICENSE)





