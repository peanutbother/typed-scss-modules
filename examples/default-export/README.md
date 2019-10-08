# Default Export Example

This example contains:

- Class names that are expected to be kebab (param) cased. Since variables cannot contain a `-` this can be achieved using an interface with default export.
- Class names that are TypeScript keywords (eg: `while`) that cannot be used as named constants.

The command to generate the proper type files would look like this (_in the root of this repository_):

```bash
yarn tsm --exportType default --nameFormat kebab "examples/default-export/**/*.scss"
```
