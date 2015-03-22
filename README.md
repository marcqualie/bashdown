# CLI Markdown Preview

A simple CLI tool for previewing markdown files in Github Flavored Markdown


## Quick Installation

    curl -s https://raw.github.com/marcqualie/bashdown/master/installer | sh


## Usage

    bd FILENAME [COMMAND]

    - FILENAME  File location
    - COMMAND   Command to pipe output to. Default: cat


## Variables

    export BASHDOWN_DEFAULT_COMMAND="open -a /Applications/Google\ Chrome.app"


## Examples

    bd README.md > README.html
    bd README.md "open -a /Applications/Google\ Chrome.app"
    bd README.md | lynx -stdin


## Thanks

[Sam Lambert](https://github.com/samlambert) for helping with the naming of this tool
