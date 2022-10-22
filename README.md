
## Wiki Lookup
Repository to list gaming-related independent wikis.

### Adding entries
Please submit additional wikis with the following format. Only include entries if it is a primary subject matter for the wiki.

Wiki name, homepage, and api are required. The rest are optional.
```json
{
	"Wiki name": {
		"homepage": "https://<url of homepage>",
		"api": "https://<url of api>",
		"companies": [
			<list of companies>
		],
		"games": [
			<list of games>
		],
		"genres": [
			<list of genres>
		],
		"series": [
			<list of series>
		],
		"systems": [
			<list of systems>
		]
	},
}
```