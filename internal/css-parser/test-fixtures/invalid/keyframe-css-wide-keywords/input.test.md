# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `invalid > keyframe-css-wide-keywords`

```javascript
CSSRoot {
	comments: Array []
	corrupt: false
	integrity: undefined
	loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 1:0-3:19
	path: RelativePath<invalid/keyframe-css-wide-keywords/input.css>
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse"}]
			location: Object {
				integrity: undefined
				language: "css"
				sourceText: undefined
				end: Position 1:18
				path: RelativePath<invalid/keyframe-css-wide-keywords/input.css>
				start: Position 1:11
			}
			description: Object {
				categoryValue: "css"
				category: Array ["parse"]
				message: RAW_MARKUP {value: "The identifier <emphasis>initial</emphasis> can't be used here."}
				advice: Array [
					log {
						category: "info"
						text: RAW_MARKUP {value: "In this position, the words <emphasis>unset</emphasis>, <emphasis>initial</emphasis>, <emphasis>inherit</emphasis>,  are CSS-wide keywords, so they are reserved."}
					}
				]
			}
		}
	]
	body: Array [
		CSSAtRule {
			name: "keyframes"
			block: undefined
			prelude: Array []
			loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 1:0-1:18
		}
		CSSRule {
			prelude: Array []
			loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 1:19-1:21
			block: CSSBlock {
				value: Array []
				startingTokenValue: "{"
				loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 1:19-1:21
			}
		}
		CSSAtRule {
			name: "keyframes"
			block: undefined
			prelude: Array []
			loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 2:0-2:18
		}
		CSSRule {
			prelude: Array []
			loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 2:19-2:21
			block: CSSBlock {
				value: Array []
				startingTokenValue: "{"
				loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 2:19-2:21
			}
		}
		CSSAtRule {
			name: "keyframes"
			block: undefined
			prelude: Array []
			loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 3:0-3:16
		}
		CSSRule {
			prelude: Array []
			loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 3:17-3:19
			block: CSSBlock {
				value: Array []
				startingTokenValue: "{"
				loc: SourceLocation invalid/keyframe-css-wide-keywords/input.css 3:17-3:19
			}
		}
	]
}
```