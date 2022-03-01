# ShellCheck for Nova

A extension for Nova which integrates [ShellCheck](https://www.shellcheck.net) for static analysis of shell
scripts in the [Nova](https://nova.app) text editor.

**[Install](https://extensions.panic.com/extensions/net.51degrees/net.51degrees.shellcheck/)**

## Development

The extension is developed in [Typescript](https://www.typescriptlang.org), which means it must be built before it
can be opened.

* `npm run build`: builds the extension
* `npm run test`: runs the tests
* `npm run lint`: runs all lints
* `npm run fix"`: fixes any fixable linter errors
* `npm run watch`: watches for changes, and rebuild the extension
