# Latex Templae for Thesis/Paper and other Stuff

# Requirements

I recommend using VSCode for writing. For compiling and everything the following plugin is required:

> [Latex Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)

You also need a working TeX-Environment, Python3 and the Python3-Module **Pygments** 

## Useful Information

Minted needs `-shell-escape` to work. Be aware to use or modify [settings.json](.vscode/settings.json) to reflect that
### main.tex

- `\include` will render each file separately as a own .aux-file and than links them together
  - you can compile each file itself
  - will always start 
- `\input` will replace the command with the actual file contents and render it completely