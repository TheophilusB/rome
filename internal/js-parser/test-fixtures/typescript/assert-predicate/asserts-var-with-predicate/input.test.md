# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > assert-predicate > asserts-var-with-predicate`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
		end: Object {
			column: 0
			line: 4
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
					identifierName: "C"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
				end: Object {
					column: 1
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "assertIsString"
								loc: Object {
									filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
									identifierName: "assertIsString"
									end: Object {
										column: 16
										line: 2
									}
									start: Object {
										column: 2
										line: 2
									}
								}
							}
							loc: Object {
								filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
								end: Object {
									column: 16
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
						}
						loc: Object {
							filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
							end: Object {
								column: 60
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
								end: Object {
									column: 60
									line: 2
								}
								start: Object {
									column: 58
									line: 2
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 2
							}
							loc: Object {
								filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
								end: Object {
									column: 16
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							rest: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
								end: Object {
									column: 57
									line: 2
								}
								start: Object {
									column: 16
									line: 2
								}
							}
							returnType: TSTypePredicate {
								asserts: true
								loc: Object {
									filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
									end: Object {
										column: 57
										line: 2
									}
									start: Object {
										column: 42
										line: 2
									}
								}
								typeAnnotation: TSStringKeywordTypeAnnotation {
									loc: Object {
										filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
										end: Object {
											column: 57
											line: 2
										}
										start: Object {
											column: 51
											line: 2
										}
									}
								}
								parameterName: JSIdentifier {
									name: "value"
									loc: Object {
										filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
										identifierName: "value"
										end: Object {
											column: 47
											line: 2
										}
										start: Object {
											column: 42
											line: 2
										}
									}
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "value"
									loc: Object {
										filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
										identifierName: "value"
										end: Object {
											column: 22
											line: 2
										}
										start: Object {
											column: 17
											line: 2
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										loc: Object {
											filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
											end: Object {
												column: 31
												line: 2
											}
											start: Object {
												column: 17
												line: 2
											}
										}
										typeAnnotation: TSUnknownKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/assert-predicate/asserts-var-with-predicate/input.ts"
												end: Object {
													column: 31
													line: 2
												}
												start: Object {
													column: 24
													line: 2
												}
											}
										}
									}
								}
							]
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
