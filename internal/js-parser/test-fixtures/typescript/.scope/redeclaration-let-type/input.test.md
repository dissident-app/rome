# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > scope > redeclaration-let-type`

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
			column: 0
			index: 29
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 11
					index: 11
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "input.ts"
					end: Object {
						column: 11
						index: 11
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "X"
							loc: Object {
								filename: "input.ts"
								identifierName: "X"
								end: Object {
									column: 5
									index: 5
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.ts"
							end: Object {
								column: 10
								index: 10
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
						init: JSStringLiteral {
							value: ""
							loc: Object {
								filename: "input.ts"
								end: Object {
									column: 10
									index: 10
									line: 1
								}
								start: Object {
									column: 8
									index: 8
									line: 1
								}
							}
						}
					}
				]
			}
		}
		TSTypeAlias {
			id: JSBindingIdentifier {
				name: "X"
				loc: Object {
					filename: "input.ts"
					identifierName: "X"
					end: Object {
						column: 6
						index: 18
						line: 2
					}
					start: Object {
						column: 5
						index: 17
						line: 2
					}
				}
			}
			typeParameters: undefined
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 16
					index: 28
					line: 2
				}
				start: Object {
					column: 0
					index: 12
					line: 2
				}
			}
			right: TSNumberKeywordTypeAnnotation {
				loc: Object {
					filename: "input.ts"
					end: Object {
						column: 15
						index: 27
						line: 2
					}
					start: Object {
						column: 9
						index: 21
						line: 2
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
