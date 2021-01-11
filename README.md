# Phel-json

Phel library for converting [Phel](https://phel-lang.org/) datastructures to and from JSON.

[![Become a Patron](https://img.shields.io/badge/Become%20a-Patron-f96854.svg?style=for-the-badge)](https://www.patreon.com/laravelista)

## Overview

This Phel library is a wrapper library around PHP `json_encode` and `json_decode` functions. It converts Phel datastructures and basic types to a format that PHP understands before calling `(php/json_encode)`.

It should also generating valid Phel datastructures from given JSON strings (*coming soon*).


## Installation

From the command line:

```bash
composer require mabasic/phel-json
```

## Usage

This Phel library has two public method:

- `(json/encode x)`
- `(json/decode x)` (*coming soon*)


```phel
(ns your\namespace
    (:require mabasic\json\json))

(println (json/encode @{"name" "Phel"  "type" "lisp"}))

# output
# {"name": "Phel", "type": "lisp"}
```

## Sponsors & Backers

I would like to extend my thanks to the following sponsors & backers for funding my open-source journey. If you are interested in becoming a sponsor or backer, please visit the [Backers page](https://mariobasic.com/backers).


## Contributing

Thank you for considering contributing to Phel-json! The contribution guide can be found [Here](https://mariobasic.com/contributing).


## Code of Conduct

In order to ensure that the open-source community is welcoming to all, please review and abide by the [Code of Conduct](https://mariobasic.com/code-of-conduct).


## License

Phel-json is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
