# Github Workflow

This repo contains class exercises carried out in the Continuous Integrations and AWS class as part of the Full Stack Web Development Program at [Business College Helsinki](https://en.bc.fi/qualifications/full-stack-web-developer-program/).

## Task

[![GH workflow](https://github.com/laurielim/REACT21K_CI-AWS_GITHUB_WORKFLOW/actions/workflows/task.yml/badge.svg)](https://github.com/laurielim/REACT21K_CI-AWS_GITHUB_WORKFLOW/actions/workflows/task.yml)

## null_or_empty

[![Node CI](https://github.com/laurielim/REACT21K_CI-AWS_GITHUB_WORKFLOW/actions/workflows/main.yml/badge.svg)](https://github.com/laurielim/REACT21K_CI-AWS_GITHUB_WORKFLOW/actions/workflows/main.yml)

A Node.js package that checks if a given string is null or empty.

### Usage

First, install the package using npm:

    npm install @skalwar/null_or_empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@skalwar/null_or_empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
