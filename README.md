# Sphinx vs code style config

* add to project

	`git submodule add git@github.com:BeliefChainOrg/editor-config.git .vscode`

* update submodule to latest commit

	`git submodule update --remote`

* required:

	* vscode eslint plugin, vscode prettier plugin, vscode solidity plugin

	* package.json devDependencies

	```
	"standard": "^10.0.3",
	"eslint": "^4.10.0",
	"eslint-config-standard": "^10.2.1",
	"eslint-plugin-import": "^2.8.0",
	"eslint-plugin-node": "^5.2.1",
	"eslint-plugin-standard": "^3.0.1"
	```

	* more ...
