# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > type-arguments > new-false-positive`

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
			index: 11
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 10
					index: 10
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSBinaryExpression {
				operator: "<"
				loc: Object {
					filename: "input.ts"
					end: Object {
						column: 9
						index: 9
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				right: JSReferenceIdentifier {
					name: "T"
					loc: Object {
						filename: "input.ts"
						identifierName: "T"
						end: Object {
							column: 9
							index: 9
							line: 1
						}
						start: Object {
							column: 8
							index: 8
							line: 1
						}
					}
				}
				left: JSNewExpression {
					arguments: Array []
					optional: undefined
					typeArguments: undefined
					loc: Object {
						filename: "input.ts"
						end: Object {
							column: 5
							index: 5
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
					callee: JSReferenceIdentifier {
						name: "A"
						loc: Object {
							filename: "input.ts"
							identifierName: "A"
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