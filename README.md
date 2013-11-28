# browserify-graph(1)

Output a graph of all the files that are required by a JS source file, using the same dependency resolution as [browserify](https://github.com/substack/node-browserify). This will recursively search for required files.

## Usage

    browserify-graph <file>

Outputs a graph of all required files, starting at `<file>`.
