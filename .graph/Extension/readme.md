# Install Extension via Command line
```
code --install-extension $extension
```
https://code.visualstudio.com/docs/editor/extension-marketplace#_command-line-extension-management


## in: Flatpak
```
flatpak run --command=bash com.visualstudio.code
# from: https://www.reddit.com/r/flatpak/comments/y58jbe/flatpak_vscode_not_allowing_use_of_certain/?rdt=64089

extension="ms-vscode-remote.remote-containers"

code --install-extension $extension
```
