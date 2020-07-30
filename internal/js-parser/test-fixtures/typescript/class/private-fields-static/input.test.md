# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > private-fields-static`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/class/private-fields-static/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/private-fields-static/input.ts"
		end: Object {
			column: 0
			index: 46
			line: 5
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "typescript/class/private-fields-static/input.ts"
					identifierName: "A"
					end: Object {
						column: 7
						index: 7
						line: 1
					}
					start: Object {
						column: 6
						index: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "typescript/class/private-fields-static/input.ts"
				end: Object {
					column: 1
					index: 45
					line: 4
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/class/private-fields-static/input.ts"
					end: Object {
						column: 1
						index: 45
						line: 4
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: Array [
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "typescript/class/private-fields-static/input.ts"
									identifierName: "x"
									end: Object {
										column: 11
										index: 21
										line: 2
									}
									start: Object {
										column: 10
										index: 20
										line: 2
									}
								}
							}
							loc: Object {
								filename: "typescript/class/private-fields-static/input.ts"
								end: Object {
									column: 11
									index: 21
									line: 2
								}
								start: Object {
									column: 9
									index: 19
									line: 2
								}
							}
						}
						value: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/private-fields-static/input.ts"
							end: Object {
								column: 12
								index: 22
								line: 2
							}
							start: Object {
								column: 2
								index: 12
								line: 2
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								index: 12
								line: 2
							}
							loc: Object {
								filename: "typescript/class/private-fields-static/input.ts"
								end: Object {
									column: 11
									index: 21
									line: 2
								}
								start: Object {
									column: 2
									index: 12
									line: 2
								}
							}
						}
					}
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "y"
								loc: Object {
									filename: "typescript/class/private-fields-static/input.ts"
									identifierName: "y"
									end: Object {
										column: 11
										index: 34
										line: 3
									}
									start: Object {
										column: 10
										index: 33
										line: 3
									}
								}
							}
							loc: Object {
								filename: "typescript/class/private-fields-static/input.ts"
								end: Object {
									column: 11
									index: 34
									line: 3
								}
								start: Object {
									column: 9
									index: 32
									line: 3
								}
							}
						}
						value: undefined
						loc: Object {
							filename: "typescript/class/private-fields-static/input.ts"
							end: Object {
								column: 20
								index: 43
								line: 3
							}
							start: Object {
								column: 2
								index: 25
								line: 3
							}
						}
						typeAnnotation: TSStringKeywordTypeAnnotation {
							loc: Object {
								filename: "typescript/class/private-fields-static/input.ts"
								end: Object {
									column: 19
									index: 42
									line: 3
								}
								start: Object {
									column: 13
									index: 36
									line: 3
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								index: 25
								line: 3
							}
							loc: Object {
								filename: "typescript/class/private-fields-static/input.ts"
								end: Object {
									column: 11
									index: 34
									line: 3
								}
								start: Object {
									column: 2
									index: 25
									line: 3
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```