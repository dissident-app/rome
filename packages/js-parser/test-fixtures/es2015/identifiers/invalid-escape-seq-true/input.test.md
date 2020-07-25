# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > identifiers > invalid-escape-seq-true`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/identifiers/invalid-escape-seq-true/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/identifiers/invalid-escape-seq-true/input.js"
		end: Object {
			column: 0
			index: 10
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "Escape sequence in keyword "}
						"true"
					]
				}
			}
			location: Object {
				filename: "es2015/identifiers/invalid-escape-seq-true/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 0
					index: 0
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/identifiers/invalid-escape-seq-true/input.js"
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
			expression: JSBooleanLiteral {
				value: true
				loc: Object {
					filename: "es2015/identifiers/invalid-escape-seq-true/input.js"
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
			}
		}
	]
}
```

### `diagnostics`

```

 es2015/identifiers/invalid-escape-seq-true/input.js:1 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Escape sequence in keyword true

    \u0074rue
    ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```