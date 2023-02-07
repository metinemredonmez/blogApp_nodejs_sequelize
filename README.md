# blogApp_nodejs_sequelize

📅 Current maintenance status

Supports modern JavaScript: ES5, ES2017, JSX, Vue and Flow type annotations.
Infers parameters, types, membership, and more. Write less documentation: let the computer write it for you.
Integrates with GitHub to link directly from documentation to the code it refers to.
Customizable output: HTML, JSON, Markdown, and more
Examples
HTML output with default template
Markdown
JSON
Documentation
Getting Started: start here
Usage: how to use documentation.js
Recipes: tricks for writing effective JSDoc docs
Node API: documentation.js's self-generated documentation
Configuring documentation.js
FAQ
Troubleshooting
Theming: tips for theming documentation output in HTML
See also: a list of projects similar to documentation.js
User Guide
Globally install documentation using the npm package manager:

$ npm install -g documentation
This installs a command called documentation in your path, that you can point at JSDoc-annotated source code to generate human-readable documentation. First, run documentation with the --help option for help:

Usage:

# generate markdown docs for index.js and files it references
documentation build index.js -f md

# generate html docs for all files in src, and include links to source files in github
documentation build src/** -f html --github -o docs

# document index.js, ignoring any files it requires or imports
documentation build index.js -f md --shallow

# validate JSDoc syntax in util.js
documentation lint util.js

# update the API section of README.md with docs from index.js
documentation readme index.js --section=API

# build docs for all values exported by index.js
documentation build --document-exported index.js

# build html docs for a TypeScript project
documentation build index.ts --parse-extension ts -f html -o docs

Commands:
  build [input..]   build documentation
  lint [input..]    check for common style and uniformity mistakes
  readme [input..]  inject documentation into your README.md

Options:
  --version  Show version number                                       [boolean]
  --help     Show help                                                 [boolean]
Contributing
We have plenty of issues that we'd love help with.

Robust and complete JSDoc support, including typedefs.
Strong support for HTML and Markdown output
Documentation coverage, statistics, and validation
documentation is an OPEN Open Source Project. This means that:

Individuals making significant and valuable contributions are given commit-access to the project to contribute as they see fit. This project is more like an open wiki than a standard guarded open source project.

Keywords
documentationformatterjsdocjsdoc3parserwebsite
