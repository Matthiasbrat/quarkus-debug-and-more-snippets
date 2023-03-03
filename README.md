# VSCode Quarkus Debug and more Snippet Extension

This VSCode extension provides snippets to improve your development experience with Quarkus framework. With this extension, you can quickly insert frequently used code snippets into your editor without having to type them manually.

## Installation

To install the extension, follow these steps:

1. Open Visual Studio Code.
2. Press `Ctrl+Shift+X` to open the Extensions panel.
3. Search for "Quarkus Snippet Extension".
4. Click on "Install".

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