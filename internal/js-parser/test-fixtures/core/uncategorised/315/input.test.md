# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 315`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/315/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/315/input.js"
		end: Object {
			column: 18
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentBlock {
			id: "0"
			value: " Multiline\nComment "
			loc: Object {
				filename: "core/uncategorised/315/input.js"
				end: Object {
					column: 10
					line: 2
				}
				start: Object {
					column: 13
					line: 1
				}
			}
		}
	]
	body: Array [
		JSBlockStatement {
			directives: Array []
			loc: Object {
				filename: "core/uncategorised/315/input.js"
				end: Object {
					column: 18
					line: 2
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: Array [
				JSThrowStatement {
					trailingComments: Array ["0"]
					loc: Object {
						filename: "core/uncategorised/315/input.js"
						end: Object {
							column: 13
							line: 1
						}
						start: Object {
							column: 2
							line: 1
						}
					}
					argument: JSReferenceIdentifier {
						name: "error"
						trailingComments: undefined
						loc: Object {
							filename: "core/uncategorised/315/input.js"
							identifierName: "error"
							end: Object {
								column: 13
								line: 1
							}
							start: Object {
								column: 8
								line: 1
							}
						}
					}
				}
				JSExpressionStatement {
					leadingComments: Array ["0"]
					loc: Object {
						filename: "core/uncategorised/315/input.js"
						end: Object {
							column: 16
							line: 2
						}
						start: Object {
							column: 10
							line: 2
						}
					}
					expression: JSReferenceIdentifier {
						name: "error"
						leadingComments: undefined
						loc: Object {
							filename: "core/uncategorised/315/input.js"
							identifierName: "error"
							end: Object {
								column: 15
								line: 2
							}
							start: Object {
								column: 10
								line: 2
							}
						}
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
