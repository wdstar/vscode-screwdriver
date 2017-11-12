# Screwdriver Pipeline and Template Editor for Visual Studio Code

This extension provides YAML validation and content assist (snippets) for editing [Screwdriver](http://screwdriver.cd/) Pipeline and Template configuration files.

## Usage

The Screwdriver editor automatically is activated when the name of the YAML file you are editing 
follows a certain pattern:

  - `**/*screwdriver*.yaml` : activates support for editing pipelines
  - `**/*template*.yaml` : activates support for editing templates.

## Features

### Content Assist

Type `Ctrl + Space` to popup a list of all symbols in your current Pipeline/Template file.

![Content Assist](https://github.com/wdstar/vscode-screwdriver/raw/master/images/content-assist.png)

## Requirements

None.

## Extension Settings

None.

## Release Notes

### 0.0.1

Initial release of vscode-screwdriver

## License

* Apache-2.0
* Icon from https://commons.wikimedia.org/wiki/File:Icon_tools.svg
