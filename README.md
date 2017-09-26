# VSTS Hello World extension

## Development

* `npm i -g tfx-cli` - Install TFS Cross Platform CLI.
* `tfx extension create --manifest-globs vss-extension.json` - Package the extension into `.vsix` file.
	* Updating existing extension requires the version update in the manifest or pass the `--rev-version` to the previous `tfx extension create` command.