# Jasmine
## VS Code Jasmine snippets
-------------------

[![Version](https://vsmarketplacebadge.apphb.com/version/baflo.JasmineSnippetsTS.svg)](https://marketplace.visualstudio.com/items?itemName=baflo.JasmineSnippetsTS)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/baflo.JasmineSnippetsTS.svg)](https://marketplace.visualstudio.com/items?itemName=baflo.JasmineSnippetsTS)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/baflo.JasmineSnippetsTS.svg)](https://marketplace.visualstudio.com/items?itemName=baflo.JasmineSnippetsTS)

This extension contains code snippets for [Jasmine][jasmine] test framework and is based on the awesome [sublime-jasmine][sublime-jusmine] package by [@NicoSantangelo][NicoSantangelo].

This extension is based on the great work of (xabios)[https://github.com/xabikos] in his project https://github.com/xabikos/vscode-javascript. Other than his project I aim at using the current `this` context in each callback function. Herefore, I use TypeScript's `function (this: CurrentThisContext) {}` notation.

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

## Supported languages (file extensions)
* TypeScript (.ts)
* TypeScript React (.tsx)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **→** means the `TAB` key.

### Specs
| Trigger      | Content |
| -------:     | ------- |
| `desc→`      | describe method |
| `xdesc→`     | xdescribe method |
| `fdesc→`     | fdescribe method |
| `it→`        | it method |
| `xit→`       | xit method |
| `fit→`       | fit method |
| `ae→`        | after each method |
| `be→`        | before each method |

### Expectations
| Trigger  | Content |
| -------: | ------- |
| `exp→` 	 | expect |
| `tb→`    | expect().toBe |
| `tbct→`  | expect().toBeCloseTo |
| `tbd→`   | expect().toBeDefined |
| `tbf→`   | expect().toBeFalsy |
| `tbgt→`  | expect().toBeGreaterThan |
| `tblt→`  | expect().toBeLessThan |
| `tbn→`   | expect().toBeNull |
| `tbt→`   | expect().toBeTruthy |
| `tbu→`   | expect().toBeUndefined |
| `tc→`    | expect().toContain |
| `te→`    | expect().toEqual |
| `thbc→`  | expect().toHaveBeenCalled |
| `thbcw→` | expect().toHaveBeenCalledWith |
| `tm→`    | expect().toMatch |
| `tt→`    | expect().toThrow |
| `tte→`   | expect().toThrowError |
| `nb→`    | expect().not.toBe |
| `nct→`   | expect().not.toBeCloseTo |
| `nd→`    | expect().not.toBeDefined |
| `nf→`    | expect().not.toBeFalsy |
| `ngt→`   | expect().not.toBeGreaterThan |
| `nlt→`   | expect().not.toBeLessThan |
| `nn→`    | expect().not.toBeNull |
| `nt→`    | expect().not.toBeTruthy |
| `nu→`    | expect().not.toBeUndefined |
| `nc→`    | expect().not.toContain |
| `ne→`    | expect().not.toEqual |
| `nm→`    | expect().not.toMatch |
| `nt→`    | expect().not.toThrow |
| `any→`   | jasmine.any |
| `oc→`    | jasmine.objectContaining |

### Spies
| Trigger  | Content |
| -------: | ------- |
|`so→`     | spyOn |
|`sct→`    | spyOn.and.callThrough |
|`scf→`    | spyOn.and.callFake |
|`spg→`     | spyOnProperty($obj,'$property', 'get') |
|`sps→`     | spyOnProperty($obj,'$property', 'set') |
|`srv→`    | spyOn.and.returnValue |
|`ss→`     | spyOn.and.stub |
|`ste→`    | spyOn.and.throwError |
|`ca→`     | spy.calls.all |
|`caa→`    | spy.calls.allArgs |
|`ca→`     | spy.calls.any |
|`caf→`    | spy.calls.argsFor |
|`cc→`     | spy.calls.count |
|`cf→`     | spy.calls.first |
|`cmr→`    | spy.calls.mostRecent |
|`cr→`     | spy.calls.reset |
|`cs→`     | createSpy |
|`cso→`    | createSpyObj |

[jasmine]: http://jasmine.github.io
[sublime-jusmine]: https://github.com/NicoSantangelo/sublime-jasmine
[NicoSantangelo]: https://github.com/NicoSantangelo
