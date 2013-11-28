# browserify-graph(1)

[![Dependency Status](https://gemnasium.com/conradz/browserify-graph.png)](https://gemnasium.com/conradz/browserify-graph)

Output a graph of all the files that are required by a JS source file, using
the same dependency resolution as
[browserify](https://github.com/substack/node-browserify). This will
recursively search for required files.

## Installation

    npm install -g browserify-graph

## Usage

    browserify-graph <file>

Outputs a graph of all required files, starting at `<file>`.
