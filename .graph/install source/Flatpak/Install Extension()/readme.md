https://www.google.com/search?q=vscode+flatpak+install+extension+command+line

use:
```
flatpak run --command=bash com.visualstudio.code
# from: https://www.reddit.com/r/flatpak/comments/y58jbe/flatpak_vscode_not_allowing_use_of_certain/?rdt=64089

extension="ms-vscode-remote.remote-containers"

code --install-extension $extension
```
