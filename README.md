## Custom Build of Iosevka
This is my custom build of the [Iosevka](https://github.com/be5invis/Iosevka) font. This build is based on Iosevka SS02(Anonymous Pro Style) with some little modifications, and has been [Nerd Font](https://github.com/ryanoasis/nerd-fonts) patched.

There are 3 versions of the font for diferent uses.

- **IosevkaSS02F** is variant with ligature support to be use in your text editor or IDE.
- **IosevkaSS02F-Term** is a variant without ligatures support with better supports for terminals.
- **IosevkaSS02F NF** is variant with ligature support and patched with the [Nerd Font](https://github.com/ryanoasis/nerd-fonts) script. Suitable for glyph enable terminals and text editors such as [OhMyZSH](https://github.com/ohmyzsh/ohmyzsh)'s [Powerlevel10K](https://github.com/romkatv/powerlevel10k), [Starship](https://github.com/starship/starship), [Spaceship ZSH](https://github.com/denysdovhan/spaceship-prompt), and VS Code.


## Download and Installation
You can download the patched and non-patched font from the [Github Release Page](https://github.com/Damia12/IosevkaSS02F/releases/).

-**Instruction for Linux**: Copy the TTF file to your fonts directory, usually in you Home directory `~/.local/share/fonts`, and run `sudo fc-cache -f -v` to refresh your system's font cache.

-**[Instruction for macOS](https://support.apple.com/en-us/HT201749)**: Right click on .ttf font file, and Install it with FontBook App.

-**[Instruction for Windows](https://support.microsoft.com/en-us/help/314960/how-to-install-or-remove-a-font-in-windows#:~:text=Select%20Start%20%3E%20Settings%20%3E%20Personalization%20%3E%20Fonts%20%2C%20and%20then%20select,will%20download%20and%20install%20automatically.)**: Download the font from the [Release Page], select the font file, right click, and select "Install for all users".

## Font Specimen
![](https://raw.githubusercontent.com/Damia12/IosevkaSS02F/main/images/IosevkaSS02F.png)

## Demo
IosevkaSS02F font when applied to VS Code text editor, using Iosevka-F Regular.
![](https://github.com/Damia12/IosevkaSS02F/blob/main/images/Demo.png?raw=true)

To be able to use font ligatures you have to activate them in VS Code settings.
![](https://github.com/Damia12/IosevkaSS02F/blob/main/images/Settings.png?raw=true)

![](https://github.com/Damia12/IosevkaSS02F/blob/main/images/fontLigatures.png?raw=true)
