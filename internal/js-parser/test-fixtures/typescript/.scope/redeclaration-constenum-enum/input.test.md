# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > scope > redeclaration-constenum-enum`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "input.ts"
		end: Object {
			column: 9
			index: 25
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		TSEnumDeclaration {
			id: JSBindingIdentifier {
				name: "X"
				loc: Object {
					filename: "input.ts"
					identifierName: "X"
					end: Object {
						column: 12
						index: 12
						line: 1
					}
					start: Object {
						column: 11
						index: 11
						line: 1
					}
				}
			}
			const: true
			members: Array []
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 15
					index: 15
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
		TSEnumDeclaration {
			id: JSBindingIdentifier {
				name: "X"
				loc: Object {
					filename: "input.ts"
					identifierName: "X"
					end: Object {
						column: 6
						index: 22
						line: 2
					}
					start: Object {
						column: 5
						index: 21
						line: 2
					}
				}
			}
			const: false
			members: Array []
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 9
					index: 25
					line: 2
				}
				start: Object {
					column: 0
					index: 16
					line: 2
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
