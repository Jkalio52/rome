# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 318`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/318/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/318/input.js"
		end: Object {
			column: 4
			line: 4
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "core/uncategorised/318/input.js"
				end: Object {
					column: 4
					line: 4
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				arguments: Array []
				loc: Object {
					filename: "core/uncategorised/318/input.js"
					end: Object {
						column: 3
						line: 4
					}
					start: Object {
						column: 1
						line: 1
					}
				}
				callee: JSFunctionExpression {
					id: undefined
					loc: Object {
						filename: "core/uncategorised/318/input.js"
						end: Object {
							column: 1
							line: 4
						}
						start: Object {
							column: 1
							line: 1
						}
					}
					head: JSFunctionHead {
						async: false
						generator: false
						hasHoistedVars: false
						params: Array []
						rest: undefined
						returnType: undefined
						thisType: undefined
						typeParameters: undefined
						loc: Object {
							filename: "core/uncategorised/318/input.js"
							end: Object {
								column: 12
								line: 1
							}
							start: Object {
								column: 10
								line: 1
							}
						}
					}
					body: JSBlockStatement {
						body: Array []
						loc: Object {
							filename: "core/uncategorised/318/input.js"
							end: Object {
								column: 1
								line: 4
							}
							start: Object {
								column: 13
								line: 1
							}
						}
						directives: Array [
							JSDirective {
								value: "use strict"
								loc: Object {
									filename: "core/uncategorised/318/input.js"
									end: Object {
										column: 14
										line: 2
									}
									start: Object {
										column: 1
										line: 2
									}
								}
							}
							JSDirective {
								value: "\0"
								loc: Object {
									filename: "core/uncategorised/318/input.js"
									end: Object {
										column: 5
										line: 3
									}
									start: Object {
										column: 1
										line: 3
									}
								}
							}
						]
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
