## Easystatic - static site generator

[![Join the chat at https://gitter.im/easystatic/easystatic](https://badges.gitter.im/easystatic/easystatic.svg)](https://gitter.im/easystatic/easystatic?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

> The easiest way to generate a static website for your project.

### Requirements

  * Mac OS X, Windows, or Linux
  * [Node.js](https://nodejs.org/) v5.0 or newer
  * `npm` v3.3 or newer (new to [npm](https://docs.npmjs.com/)?)
  * `node-gyp` prerequisites mentioned [here](https://github.com/nodejs/node-gyp)

### How to Install

```sh
$ npm install easystatic  
```

### How to Use

To build the site and launch it in a browser run:

```
$ es start <path>
```

..where `<path>` is the name of the directory with `.md` files.

To deploy the site run:

```sh
$ es deploy <path> --repo=<repo> --domain=<domain>
```

..where `<repo>` is a GitHub repository, and `<domain>` is a custom domain name
for your site. For example:

```sh
$ es deploy docs --repo=easystatic/easystatic.github.io --domain=easystatic.com
```

### Licence

Copyright © 2016 Eeasystatic [contributors](https://github.com/easystatic/easystatic/graphs/contributors).
This source code is licensed under the Apache 2.0 license found in the
[LICENSE.txt](https://github.com/easystatic/easystatic/blob/master/LICENSE.txt) file.
The documentation to the project is licensed under the [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/) license.
