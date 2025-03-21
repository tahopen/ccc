# Tahopen Community Charting Components

**CCC** is a charting library for web documents.
It can generate charts in SVG or VML (for IE8 support).

**CCC** is one of the _tools_ of the **CTools** family.

If you want to know more, checkout the [CCC site](https://webdetails.github.io/ccc/).

#### Pre-requisites for building the project:
* Maven, version 3+
* Java JDK 1.8

#### Building it

This is a maven project, and to build it use the following command
```
mvn clean install
```
The build result will be a Pentaho Plugin located in *assembly/target/ccc-***.zip*. Then, this package can be dropped
inside your system folder.


#### Building the example site:

Refer to the [Contributing](CONTRIBUTING.md) document.

#### Running the tests
Install karma

```
$ npm install -g karma-cli
```
Then run
```nix
$ karma start ccc-js/src/test/config/javascript/karma.conf.js
```
