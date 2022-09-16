# rscan

Phantom dependencies scanner with Rust.

## What's this package

Check that your Node.js projects contains Phantom dependencies.

## How to work

1. collect your `dependencies` and `devDependencies` from `package.json` files.
2. scan your source code files.
3. check that `import` or `require` statement contains dependency that is not in package.json.
