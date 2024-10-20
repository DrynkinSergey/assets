Paste this lines inside your file

```
"rafc": {
		"prefix": "rafc",
		"body": [
			"export const ${TM_FILENAME_BASE} = () => {",
			"  return <div>${1}</div>",
			"}"
		],
		"description": "Create custom element"
	},
	"rafce": {
		"prefix": "rafce",
		"body": [
			"const ${TM_FILENAME_BASE} = () => {",
			"  return <div>${1}</div>",
			"}",
			"export default ${TM_FILENAME_BASE}"
		],
		"description": "Create custom element export default"
	},
```
