# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > parameter-default-inside-function-inside-generator`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 1
			index: 47
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "fn"
				loc: Object {
					filename: "input.js"
					identifierName: "fn"
					end: Object {
						column: 12
						index: 12
						line: 1
					}
					start: Object {
						column: 10
						index: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 1
					index: 47
					line: 3
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 14
						index: 14
						line: 1
					}
					start: Object {
						column: 12
						index: 12
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 1
						index: 47
						line: 3
					}
					start: Object {
						column: 15
						index: 15
						line: 1
					}
				}
				body: Array [
					JSFunctionDeclaration {
						id: JSBindingIdentifier {
							name: "fn2"
							loc: Object {
								filename: "input.js"
								identifierName: "fn2"
								end: Object {
									column: 14
									index: 31
									line: 2
								}
								start: Object {
									column: 11
									index: 28
									line: 2
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 28
								index: 45
								line: 2
							}
							start: Object {
								column: 2
								index: 19
								line: 2
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 28
									index: 45
									line: 2
								}
								start: Object {
									column: 26
									index: 43
									line: 2
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 25
									index: 42
									line: 2
								}
								start: Object {
									column: 14
									index: 31
									line: 2
								}
							}
							params: Array [
								JSBindingAssignmentPattern {
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 24
											index: 41
											line: 2
										}
										start: Object {
											column: 15
											index: 32
											line: 2
										}
									}
									right: JSReferenceIdentifier {
										name: "yield"
										loc: Object {
											filename: "input.js"
											identifierName: "yield"
											end: Object {
												column: 24
												index: 41
												line: 2
											}
											start: Object {
												column: 19
												index: 36
												line: 2
											}
										}
									}
									left: JSBindingIdentifier {
										name: "x"
										loc: Object {
											filename: "input.js"
											identifierName: "x"
											end: Object {
												column: 16
												index: 33
												line: 2
											}
											start: Object {
												column: 15
												index: 32
												line: 2
											}
										}
										meta: JSPatternMeta {
											optional: undefined
											typeAnnotation: undefined
											loc: Object {
												filename: "input.js"
												end: Object {
													column: 16
													index: 33
													line: 2
												}
												start: Object {
													column: 15
													index: 32
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