# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > template-literal-invalid-escapes-untagged > 45`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "experimental/template-literal-invalid-escapes-untagged/45/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/template-literal-invalid-escapes-untagged/45/input.js"
		end: Object {
			column: 5
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Invalid escape sequence in template"}]}
			}
			location: Object {
				filename: "experimental/template-literal-invalid-escapes-untagged/45/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 2
					line: 1
				}
				start: Object {
					column: 2
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/template-literal-invalid-escapes-untagged/45/input.js"
				end: Object {
					column: 5
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSTemplateLiteral {
				expressions: Array []
				loc: Object {
					filename: "experimental/template-literal-invalid-escapes-untagged/45/input.js"
					end: Object {
						column: 5
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				quasis: Array [
					JSTemplateElement {
						cooked: "\\u{"
						raw: "\\u{"
						tail: true
						loc: Object {
							filename: "experimental/template-literal-invalid-escapes-untagged/45/input.js"
							end: Object {
								column: 4
								line: 1
							}
							start: Object {
								column: 1
								line: 1
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

 experimental/template-literal-invalid-escapes-untagged/45/input.js:1:2 parse/js ━━━━━━━━━━━━━━━━━━━

  ✖ Invalid escape sequence in template

    `\u{`
      ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
