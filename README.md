# Jason
![Package Name](https://img.shields.io/badge/dynamic/yaml?color=%2332a852&label=Package%20Name&query=%24.name&url=https%3A%2F%2Fraw.githubusercontent.com%2Falta-lang%2Fjason%2Fmaster%2Fpackage.alta.yaml)
![Version](https://img.shields.io/badge/dynamic/yaml?color=a61900&label=Version&query=%24.version&url=https%3A%2F%2Fraw.githubusercontent.com%2Falta-lang%2Fjason%2Fmaster%2Fpackage.alta.yaml)
[![License](https://img.shields.io/github/license/alta-lang/jason?color=%23428bff)](LICENSE)

A simple little [JSON](https://www.json.org/) parser and stringifier implemented purely in Alta.

# Building the tests
Make sure you have the [Alta Compiler](https://github.com/alta-lang/alta) installed, and run this in a terminal in the project directory:
```alta
altac -c .
```
The simple parse-and-stringify binary will be located in `alta-build/_build/bin/jason`.
Run it with the path to a JSON file and it will parse it and then print the stringified result.
