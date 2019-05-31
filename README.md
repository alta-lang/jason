# Jason
A simple little [JSON](https://www.json.org/) parser and stringifier implemented purely in Alta.

# Building the tests
Make sure you have the [Alta Compiler](https://github.com/alta-lang/alta) installed, and run this in a terminal in the project directory:
```alta
altac -c .
```
The simple parse-and-stringify binary will be located in `alta-build/_build/bin/jason`.
Run it with the path to a JSON file and it will parse it and then print the stringified result.
