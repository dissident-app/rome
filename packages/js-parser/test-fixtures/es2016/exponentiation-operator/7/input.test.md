# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2016 > exponentiation-operator > 7`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2016/exponentiation-operator/7/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2016/exponentiation-operator/7/input.js"
		end: Object {
			column: 13
			index: 13
			line: 1
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
				filename: "es2016/exponentiation-operator/7/input.js"
				end: Object {
					column: 13
					index: 13
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSBinaryExpression {
				operator: "*"
				loc: Object {
					filename: "es2016/exponentiation-operator/7/input.js"
					end: Object {
						column: 13
						index: 13
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				right: JSNumericLiteral {
					value: 2
					format: undefined
					loc: Object {
						filename: "es2016/exponentiation-operator/7/input.js"
						end: Object {
							column: 13
							index: 13
							line: 1
						}
						start: Object {
							column: 12
							index: 12
							line: 1
						}
					}
				}
				left: JSBinaryExpression {
					operator: "**"
					loc: Object {
						filename: "es2016/exponentiation-operator/7/input.js"
						end: Object {
							column: 8
							index: 8
							line: 1
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
					left: JSNumericLiteral {
						value: 2
						format: undefined
						loc: Object {
							filename: "es2016/exponentiation-operator/7/input.js"
							end: Object {
								column: 2
								index: 2
								line: 1
							}
							start: Object {
								column: 1
								index: 1
								line: 1
							}
						}
					}
					right: JSUnaryExpression {
						operator: "-"
						prefix: true
						loc: Object {
							filename: "es2016/exponentiation-operator/7/input.js"
							end: Object {
								column: 8
								index: 8
								line: 1
							}
							start: Object {
								column: 6
								index: 6
								line: 1
							}
						}
						argument: JSNumericLiteral {
							value: 1
							format: undefined
							loc: Object {
								filename: "es2016/exponentiation-operator/7/input.js"
								end: Object {
									column: 8
									index: 8
									line: 1
								}
								start: Object {
									column: 7
									index: 7
									line: 1
								}
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