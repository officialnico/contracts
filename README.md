[![banner](https://raw.githubusercontent.com/oceanprotocol/art/master/github/repo-banner%402x.png)](https://oceanprotocol.com)

[![Build Status](https://travis-ci.com/oceanprotocol/contracts.svg?token=soMi2nNfCZq19zS1Rx4i&branch=develop)](https://travis-ci.com/oceanprotocol/contracts)

# Ocean Protocol Contracts

This is in alpha state and you can expect running into problems. If you run into them, please open up a [new issue](/issues).

## Table of Contents

  - [Get Started](#get-started)
     - [Local development](#local-development)
  - [Testing](#testing)
     - [Code Linting](#code-linting)
  - [Networks](#networks)
  - [Packages](#packages)
  - [Documentation](#documentation)
  - [Contributing](#contributing)
  - [Prior Art](#prior-art)
  - [License](#license)

# Get Started

For local development of the `contracts` setup the development environment on your machine as follows:

### Local development

As a pre-requisite, you need:

- Node.js
- npm

Note: For MacOS, make sure to have `node@10` installed.

Clone the project and install all dependencies:

```bash
git clone git@github.com:oceanprotocol/contracts.git
cd contracts/

# TODO

TODO

```

TODO:

```bash
TODO
```

TODO:

```bash
TODO
```


# Testing

Run tests with 

```bash
npm run test:unit
npm run test:integration
```

### Code Linting

Linting is setup for `JavaScript` with [ESLint](https://eslint.org) & Solidity with [Ethlint](https://github.com/duaraghav8/Ethlint).

Code style is enforced through the CI test process, builds will fail if there're any linting errors.

# Networks

### Testnets

TBD

### Mainnet

TBD


## Documentation

* [Contracts Documentation](doc/contracts/README.md)
* [Release process](doc/RELEASE_PROCESS.md)
* [Packaging of libraries](doc/PACKAGING.md)

## Contributing

See the page titled "[Ways to Contribute](https://docs.oceanprotocol.com/concepts/contributing/)" in the Ocean Protocol documentation.



## Prior Art

This project builds on top of the work done in open source projects:
- [zeppelinos/zos](https://github.com/zeppelinos/zos)
- [OpenZeppelin/openzeppelin-eth](https://github.com/OpenZeppelin/openzeppelin-eth)

## License

```
Copyright 2018 Ocean Protocol Foundation

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```