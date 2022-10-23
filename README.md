
## Wiki Lookup
A repository to list gaming-related independent wikis.

### Inclusion criteria
Any gaming wiki which meets the following criteria can be added to the list:
* Primary focus of the wiki must be computer or video games.
* Should be hosted on a site that doesn't cross-promote individual wikis across their network, unless they host fewer than 42 wikis.
* The wiki should be continuously online. Any wikis that become unresponsive for extended periods of time will be removed.
* Currently, the wiki must be using the [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) software. Please open an issue for additional wiki software will be accepted in the future.

### Adding entries
Please submit wikis with the following format. Only include entries if it is a primary subject matter for the wiki.

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
