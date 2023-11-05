# install-source: Flatpak

# Problem: Terminal "preload host spawn"
sch: https://www.google.com/search?q=flatpak+vscode+terminal
- https://www.google.com/search?q=preload-host-spawn-strategy%5D+Warning%3A+waitpid+override+ignores+groups

Discuss: https://github.com/flathub/com.visualstudio.code/issues/370

## Solution:
- works: https://github.com/flathub/com.visualstudio.code/issues/370#issuecomment-1666515496

>My settings.json
>```
>"terminal.integrated.env.linux": {
>  "LD_PRELOAD": null,
>},
>```

# Problem: /usr/bin/{app} not found
src: https://www.google.com/search?q=flatpak+vscode+command+not+found, https://www.google.com/search?q=flatpak+vscode+bin+not+found

## Solution: Dev containers extension
https://raduzaharia.medium.com/using-the-vscode-flatpak-distribution-a275d59ff1c7

## Solution: SDK extension
- https://www.reddit.com/r/flatpak/comments/y58jbe/flatpak_vscode_not_allowing_use_of_certain/?rdt=64089

## Solution: adding to path
- https://www.reddit.com/r/flatpak/comments/lm2lln/vscode_cant_access_usrbin_despite_access_granted/

## Try:
- https://www.reddit.com/r/flatpak/comments/y58jbe/flatpak_vscode_not_allowing_use_of_certain/
- Flatseal https://discussion.fedoraproject.org/t/how-do-i-get-vscodium-to-use-the-same-shell-environment-as-the-rest-of-my-system/80178/4

## Relation: settings.json
- sch: https://www.google.com/search?q=vscode+settings.json
- https://stackoverflow.com/questions/65908987/how-to-open-visual-studio-codes-settings-json-file

## discuss:
- https://www.reddit.com/r/Fedora/comments/14cezl0/getting_vs_codium_setup_properly_with_flatpak/
- https://github.com/orgs/ublue-os/discussions/155#discussioncomment-6025057
