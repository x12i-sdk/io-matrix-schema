# @x12i/io-matrix-schema usage example

Types, Zod schemas, and utilities for the Object–Property I/O Matrix format.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `1.1.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- A consumer needs the following capability: Types, Zod schemas, and utilities for the Object–Property I/O Matrix format.
- A producer and consumer of io-matrix-schema data need to share the published type or validation contract before exchanging payloads.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/io-matrix-schema)
- [Implementation monorepo](https://github.com/x12i/io-matrix)
- [Reviewed package source](https://github.com/x12i/io-matrix/tree/cd362f10fc0d9cf9618292933afbc82c159028ad/packages/schema)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
