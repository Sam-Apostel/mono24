# Mono24
A modern monochrome black and white theme.

## Examples
![screenshot](https://github.com/Sam-Apostel/mono24/blob/main/assets/screenshot.png?raw=true)


## Supported languages
- tsx

## Development

1. use `f5` to run the vscode extension development host
2. activate `> Developer: Inspect editor tokens and scopes`
> To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.
1. Versioniong:
```shell
npm version [major | minor | patch]
```

1. build the extension:
```shell
vsce package
```
This creates a `.vsix` file. You can install a `.vsix` using `> Extensions: Install from VSIX...`

## Deploying to the VSCode Marketplace
```shell
vsce publish
```