# Change Log

This project adheres to [Semantic Versioning](http://semver.org/).  
Every release, along with the migration instructions, is documented on the Github [Releases](https://github.com/xabikos/vscode-jasmine/releases) page.

[] 0.x.x
- `async` suggestion includes trailing space
- Don't like mixed function types. All callbacks are classic functions.
- Use double-quotes

[2019/01/30] 0.1.1
- `async` keywords are optional

[2019/01/30] 0.1.0
- Reviewed and removed `this` context from `spyOn` and `describe` callbacks. Turned these back to fat arrow functions.
- Made all callback functions async

[2019/01/29]

- Changed all callback functions to use format `function (this: CurrentThisContext) {}` instead of fat arrow notation.
