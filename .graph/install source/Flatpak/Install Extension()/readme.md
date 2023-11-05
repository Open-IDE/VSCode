https://www.google.com/search?q=vscode+flatpak+install+extension+command+line

use:
```
extension="ms-vscode-remote.remote-containers"

flatpak run --command=bash com.visualstudio.code

code --install-extension $extension
# from: https://www.reddit.com/r/flatpak/comments/y58jbe/flatpak_vscode_not_allowing_use_of_certain/?rdt=64089
```
