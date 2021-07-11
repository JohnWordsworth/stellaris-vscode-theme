# Stellaris Inspired VS Code Theme

This is a VS Code color theme inspired by Stellaris, the space-faring Grand-Strategy Game by Paradox Interactive. 

The theme is designed around the green/orange colour theme of Stellaris but also strives to maintain a good level of readability for code.

**Note.** In this initial version, very little attention has been paid to the styles for code syntax - they are mostly the base colours provided by the default dark theme. I intend to tweak these as I use the theme in the future, and will push changes if I find new combinations that work particularly well.


## Preview

<div align="center">
	[Preview Image](/docs/theme-preview.png "Stellaris VS Code Theme Preview")]
</div>


## Installation

I intend to upload this theme to the VS Marketplace in the future, but for now you will need to follow these steps to install the theme manually. 

1. Navigate to your extensions directory;

* `Windows %USERPROFILE%\.vscode\extensions`
* `macOS ~/.vscode/extensions`
* `Linux ~/.vscode/extensions`

2. Create a directory for the extension files to live in. I used `johnwordsworth.stellaris-vscode-theme-0.1.0`.

3. Copy the `packages.json` file and the `themes` directory from the Git repository into the new folder.

4. Restart VSCode and change your colour theme - Stellaris VS Code Theme should now exist in the list of available themes.


## Development Instructions

In order to further tweak this theme, you should download the git repository and open the root directory as a project in VS Code. Then you simply need to hit F5 to have VS Code launch a second window (Extension Development Host). In this window, you should be able to go to "File -> Preferences -> Color Theme" and manually select 'Stellaris VS Code Theme'. The development window will then automatically update with the new colours whenever the source file changes.


## Contributing

If you would like to make changes and contribute towards this theme, I would be happy to consider any contributions. Please note however, this is just a side-project and I will go through periods where I am able to accept upgrades but sometimes I will be busy and might not reply for some time.


## Thanks

Many thanks to Paradox Interactive for making [Stellaris](https://store.steampowered.com/app/281990/Stellaris/) in the first place - it's a great space-based grand-strategy-game. Note that I've not got explicit permission from Paradox Interactive to release this theme, but I am releasing this without the intention of ever making any money and it's simply a bit of fun while I experiment with VS Code extensions.