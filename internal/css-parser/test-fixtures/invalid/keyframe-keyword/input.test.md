# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `invalid > keyframe-keyword`

```javascript
CSSRoot {
	comments: Array []
	corrupt: false
	integrity: undefined
	loc: SourceLocation invalid/keyframe-keyword/input.css 1:0-7:1
	path: RelativePath<invalid/keyframe-keyword/input.css>
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse"}]
			location: Object {
				integrity: undefined
				language: "css"
				sourceText: undefined
				end: Position 2:5
				path: RelativePath<invalid/keyframe-keyword/input.css>
				start: Position 2:1
			}
			description: Object {
				categoryValue: "css"
				category: Array ["parse"]
				message: RAW_MARKUP {value: "The keyword <emphasis>form</emphasis> is not accepted as valid keyframe name."}
				advice: Array [
					log {
						category: "info"
						text: RAW_MARKUP {value: "Did you mean <emphasis>from</emphasis> or <emphasis>to</emphasis>?"}
					}
				]
			}
		}
	]
	body: Array [
		CSSAtRule {
			name: "keyframes"
			prelude: Array []
			loc: SourceLocation invalid/keyframe-keyword/input.css 1:0-3:1
			block: CSSKeyframe {
				name: CSSKeyframeName {
					value: CSSRaw {
						value: "foo"
						loc: SourceLocation invalid/keyframe-keyword/input.css 1:11-1:11
					}
					loc: SourceLocation invalid/keyframe-keyword/input.css 1:11-1:14
				}
				value: Array []
				loc: SourceLocation invalid/keyframe-keyword/input.css 1:10-3:1
			}
		}
		CSSAtRule {
			name: "keyframes"
			prelude: Array []
			loc: SourceLocation invalid/keyframe-keyword/input.css 5:0-7:1
			block: CSSKeyframe {
				name: CSSKeyframeName {
					value: CSSRaw {
						value: "foo"
						loc: SourceLocation invalid/keyframe-keyword/input.css 5:11-5:11
					}
					loc: SourceLocation invalid/keyframe-keyword/input.css 5:11-5:14
				}
				value: Array []
				loc: SourceLocation invalid/keyframe-keyword/input.css 5:10-7:1
			}
		}
	]
}
```