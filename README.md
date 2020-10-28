# project_name
Repo to save various files and lists needed when migrating to a new OS.

<details>
<summary><b>Table of Content</b></summary>

- [about](#about)
- [cli-software I like](#cli-software-i-like)
- [ui-software I like](#ui-software-i-like)
- [vscode extensions](#vscode-extensions)
- [.-files](#-files)
</details>

## about
I am currently on fedora31

## cli-software I like
| tool                                                       | get from                                                                                                         |
| :--------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------- |
| [bat](https://github.com/sharkdp/bat)                      | `dnf install bat`                                                                                                |
| [curl](https://github.com/curl/curl)                       | `dnf install curl`                                                                                               |
| ~~[docker](https://docs.docker.com/install/)~~ -> podman   |                                                                                                                  |
| [docker-compose](https://docs.docker.com/compose/install/) | multiple steps (see website)                                                                                     |
| [exa](https://github.com/ogham/exa)                        | `dnf install exa`                                                                                                |
| [flatpak](https://www.flatpak.org/)                        | preinstalled                                                                                                     |
| git (later version)                                        | `dnf install git-all`                                                                                            |
| [htop](https://github.com/hishamhm/htop)                   | `dnf install htop`                                                                                               |
| [ipython](https://github.com/ipython/ipython)              | `install python3-ipython`                                                                                        |
| [(ohmy)zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/)      | multiple steps (see website)                                                                                     |
| python                                                     | preinstalled                                                                                                     |
| [poetry](https://python-poetry.org/)                       | multiple steps ([see website](https://github.com/python-poetry/poetry#installation))                             |
| [podman](https://podman.io/)                               | preinstalled                                                                                                     |
| [ripgrep](https://github.com/BurntSushi/ripgrep)           |                                                                                                                  |
| ~~[snapd](https://github.com/snapcore/snapd)~~ -> flatpak  |                                                                                                                  |
| [tlp](https://linrunner.de/en/tlp/tlp.html)                | multiple steps ([see website](https://linrunner.de/en/tlp/docs/tlp-linux-advanced-power-management.html#fedora)) |
| [tmux](https://github.com/tmux/tmux/wiki)                  | preinstalled                                                                                                     |
| [tree](http://mama.indstate.edu/users/ice/tree/)           | preinstalled                                                                                                     |
| [nvim](https://neovim.io/)                                 | `dnf install nvim`                                                                                               |

## ui-software I like
| tool                                                                                  | get from                                                                                                |
| :------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------ |
| [datagrip](https://www.jetbrains.com/datagrip/)                                       |                                                                                                         |
| [firefox](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox) developer edition | `flatpak install --from https://firefox-flatpak.mojefedora.cz/org.mozilla.FirefoxDevEdition.flatpakref` |
| ~~[terminator](https://launchpad.net/terminator/)~~ -> tmux                           |                                                                                                         |
| thunderbird                                                                           | `flatpak install flathub org.mozilla.Thunderbird`                                                       |
| [vscode](https://github.com/Microsoft/vscode)                                         | `dnf install code`                                                                                      |

## vscode extensions
* Better TOML
* Git Graph
* Markdown All in One
* Python
* ~~Rust (rls)~~ -> [rust-analyzer](https://rust-analyzer.github.io/)
* Visual Studio IntelliCode
* YAML


## .-files
* [`.aliases`](.aliases)
* [`.gitconfig`](.gitconfig)
* [`.zshrc`](.zshrc)
