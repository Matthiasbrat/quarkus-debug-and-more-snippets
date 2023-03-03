<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=matthiasbrat.quarkus-debug-snippets">
    <img src="https://raw.githubusercontent.com/Matthiasbrat/quarkus-debug-and-more-snippets/main/logo.png" alt="logo" width=72 height=72>
  </a>

  <h3 align="center">Quarkus debug and more snippets</h3>

  <p align="center">
    This VSCode extension provides snippets to improve your development experience with Quarkus framework. basic CRUD requests snippets and debug configurations are provided.
    <br>
    <a href="https://github.com/Matthiasbrat/quarkus-debug-and-more-snippets/issues/new?template=bug.md">Report bug</a>
    ·
    <a href="https://github.com/Matthiasbrat/quarkus-debug-and-more-snippets/issues/new?template=feature.md&labels=feature">Request feature</a>
  </p>
</p>

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

<hr/>

## Table of contents

- [Installation](#installation)
- [Snippets](#snippets)
- [Contributing](#contributing)
- [Copyright and license](#copyright-and-license)


## Installation

To install the extension, follow these steps:

1. Open Visual Studio Code.
2. Press `Ctrl+Shift+X` to open the Extensions panel.
3. Search for "Quarkus debug snippets and more".
4. Click on "Install".

or just follow this link : https://marketplace.visualstudio.com/items?itemName=matthiasbrat.quarkus-debug-snippets

## Snippets

This extension provides the following Quarkus snippets:

### Quarkus Debug

- `quarkus debug global config`: Global configuration for debugging Quarkus applications. Contains tasks.json, settings.json and launch.json
    - `Quarkus-debug: config.json` or `q-d-c`
<p></p>

- `quarkus debug launch.json config file`: Configuration for the launch.json file for debugging Quarkus applications.
    - `Quarkus-debug: launch.json` or `q-d-l`
<p></p>

- `quarkus debug settings.json config file`: Configuration for the settings.json file for debugging Quarkus applications.
    - `Quarkus-debug: settings.json` or `q-d-s`
<p></p>

- `quarkus debug settings.json config file`: Configuration for the tasks.json file for debugging Quarkus applications.
    - `Quarkus-debug: settings.json` or `q-d-s`

### Quarkus HTTP Requests

- `quarkus get request`: Inserts code for sending a GET request to a Quarkus application.
    - `Quarkus-request: GET` or `q-g`
<p></p>

- `quarkus post request`: Inserts code for sending a POST request to a Quarkus application.
    - `Quarkus-request: POST` or `q-p`
<p></p>

- `quarkus put request`: Inserts code for sending a PUT request to a Quarkus application.
    - `Quarkus-request: PUT` or `q-u`
<p></p>

- `quarkus delete request`: Inserts code for sending a DELETE request to a Quarkus application.
    - `Quarkus-request: DELETE` or `q-d`
<p></p>

- `quarkus get request with path parameters`: Inserts code for sending a GET request with path parameters to a Quarkus application.
    - `Quarkus-request: GET with path parameters` or `q-g-p`

## Contributing

Do whatever and ask for a merge request if you want to contribute 👍.

## Copyright and license

Code released under the [GNU GENERAL PUBLIC LICENSE](https://www.gnu.org/licenses/gpl-3.0.en.html).
You can take a look at the [license file](https://github.com/Matthiasbrat/quarkus-debug-and-more-snippets/blob/main/LICENSE.md)

Enjoy 🐸