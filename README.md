# VSCode Syntax Extension for CSTOL procedure language

Supports syntax highlighting for `.prc` file format. 

To use this extension go: 
- `VSCode -> Extensions -> More Option -> Install from VSIX`
- Choose `prc-X.X.X.vsix`


### Snippets
1. To customize snippets for `.prc` go: `File -> Preferences -> Configure User Snippets`
2. Select `prc`
3. `prc.json` will be created.
4. Paste to `prc.json`:

```json
{
	"If snippet": {
		"prefix": "if",
		"body": [
			"if ",
			"",
			"endif"
		],
		"description": "Insert 'if' statement with 'endif'"
	},
	"Loop snippet": {
		"prefix": "loop",
		"body": [
			"loop ",
			"\t",
			"endloop"
		],
		"description": "Insert 'loop' statement with 'endloop'"
	},
	"Begin snippet": {
		"prefix": "begin ",
		"body": [
			"begin ",
			"",
			"endproc"
		],
		"description": "Insert 'begin' statement with 'endproc'"
	}
	
}
```
