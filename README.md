## A lightweight template engine

[![Greenkeeper badge](https://badges.greenkeeper.io/axetroy/pag.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/axetroy/pag.svg?branch=master)](https://travis-ci.org/axetroy/pag)
[![Coverage Status](https://coveralls.io/repos/github/axetroy/pag/badge.svg?branch=master)](https://coveralls.io/github/axetroy/pag?branch=master)
[![Dependency](https://david-dm.org/axetroy/pag.svg)](https://david-dm.org/axetroy/pag)
![License](https://img.shields.io/badge/license-Apache-green.svg)
[![Prettier](https://img.shields.io/badge/Code%20Style-Prettier-green.svg)](https://github.com/prettier/prettier)
![Node](https://img.shields.io/badge/node-%3E=6.0-blue.svg?style=flat-square)
[![npm version](https://badge.fury.io/js/%40axetroy%2Fpag.svg)](https://badge.fury.io/js/%40axetroy%2Fpag)
![Size](https://github-size-badge.herokuapp.com/axetroy/pag.svg)

[Try it out](https://axetroy.github.io/pag)

> This is a template engine base on AST
> It's useful to help you learn how to write a compiler

## Usage

```javascript
const pag = require("@axetroy/pag");

pag("hello {{name}}", { name: "world" }); // hello world
```

## Contributing

[Contributing Guide](https://github.com/axetroy/pag/blob/master/CONTRIBUTING.md)

如果你觉得项目不错，不要吝啬你的 star.

长期造轮子，欢迎 follow.

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

| [<img src="https://avatars1.githubusercontent.com/u/9758711?v=3" width="100px;"/><br /><sub>Axetroy</sub>](http://axetroy.github.io)<br />[💻](https://github.com/axetroy/pag/commits?author=axetroy) [🐛](https://github.com/axetroy/pag/issues?q=author%3Aaxetroy) 🎨 |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |


<!-- ALL-CONTRIBUTORS-LIST:END -->

## License

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Faxetroy%2Fpag.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Faxetroy%2Fpag?ref=badge_large)
