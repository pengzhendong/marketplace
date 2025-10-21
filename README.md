# VS Code Extension Downloader

This is a simple and practical tool that helps you directly obtain download links for VS Code extensions, allowing you to download `.vsix` files for local installation.

## Usage

1. Search for and find the extension you want in the VS Code official marketplace
2. Copy the `itemName` parameter from the extension page URL
3. Append this parameter to the tool's URL
4. Visit the newly generated link to automatically redirect to the extension's download address

## Usage Examples

**Official Marketplace Link:**
https://marketplace.visualstudio.com/items?itemName=MarsCode.marscode-extension

**Corresponding Download Link:**
https://pengzhendong.github.io/marketplace?itemName=MarsCode.marscode-extension

Visit the download link and your browser will automatically redirect to the `.vsix` file download address for the extension.

## Version Parameter

You can specify a particular version of the extension by adding the `version` parameter to the URL. If no version is specified, the latest version will be downloaded by default.

**Example with Version Parameter:**
https://pengzhendong.github.io/marketplace?itemName=MarsCode.marscode-extension&version=1.3.9
