# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-primary-literal-regular-expression > migrated_0012`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
		end: Object {
			column: 21
			index: 21
			line: 1
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
				filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
				end: Object {
					column: 21
					index: 21
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
					end: Object {
						column: 21
						index: 21
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
							name: "x"
							loc: Object {
								filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
								identifierName: "x"
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
							filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
							end: Object {
								column: 21
								index: 21
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
						init: JSRegExpLiteral {
							global: true
							insensitive: false
							multiline: false
							noDotNewline: false
							sticky: false
							unicode: false
							loc: Object {
								filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
								end: Object {
									column: 21
									index: 21
									line: 1
								}
								start: Object {
									column: 8
									index: 8
									line: 1
								}
							}
							expression: JSRegExpSubExpression {
								loc: Object {
									filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
									end: Object {
										column: 18
										index: 19
										line: 1
									}
									start: Object {
										column: 9
										index: 9
										line: 1
									}
								}
								body: Array [
									JSRegExpCharacter {
										value: "="
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
											end: Object {
												column: 10
												index: 10
												line: 1
											}
											start: Object {
												column: 9
												index: 9
												line: 1
											}
										}
									}
									JSRegExpQuantified {
										lazy: false
										max: undefined
										min: 1
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
											end: Object {
												column: 18
												index: 18
												line: 1
											}
											start: Object {
												column: 10
												index: 10
												line: 1
											}
										}
										target: JSRegExpGroupCapture {
											name: undefined
											loc: Object {
												filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
												end: Object {
													column: 18
													index: 18
													line: 1
												}
												start: Object {
													column: 10
													index: 10
													line: 1
												}
											}
											expression: JSRegExpSubExpression {
												loc: Object {
													filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
													end: Object {
														column: 17
														index: 17
														line: 1
													}
													start: Object {
														column: 11
														index: 11
														line: 1
													}
												}
												body: Array [
													JSRegExpCharSet {
														invert: true
														loc: Object {
															filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
															end: Object {
																column: 17
																index: 17
																line: 1
															}
															start: Object {
																column: 11
																index: 11
																line: 1
															}
														}
														body: Array [
															JSRegExpCharacter {
																value: "="
																loc: Object {
																	filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
																	end: Object {
																		column: 14
																		index: 14
																		line: 1
																	}
																	start: Object {
																		column: 13
																		index: 13
																		line: 1
																	}
																}
															}
															JSRegExpWhiteSpaceCharacter {
																loc: Object {
																	filename: "esprima/expression-primary-literal-regular-expression/migrated_0012/input.js"
																	end: Object {
																		column: 16
																		index: 16
																		line: 1
																	}
																	start: Object {
																		column: 14
																		index: 14
																		line: 1
																	}
																}
															}
														]
													}
												]
											}
										}
									}
								]
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