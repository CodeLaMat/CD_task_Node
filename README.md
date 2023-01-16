# CD_task_Node

[![Node CI](https://github.com/CodeLaMat/CD_task_Node/actions/workflows/whatever.yml/badge.svg)](https://github.com/CodeLaMat/CD_task_Node/actions/workflows/whatever.yml)

A Node.js package that checks, if a given string is null or empty.

## Usage

First, install the package using npm:

    npm install @sCodeLaMat/CD_task_Node --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@sCodeLaMat/CD_task_Node');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
