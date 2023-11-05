# install-source: Flatpak
##  Guide:
Top.Favorite!: https://raduzaharia.medium.com/using-the-vscode-flatpak-distribution-a275d59ff1c7

# Problem: Terminal
sch: https://www.google.com/search?q=flatpak+vscode+terminal
- https://www.google.com/search?q=preload-host-spawn-strategy%5D+Warning%3A+waitpid+override+ignores+groups

Discuss: https://github.com/flathub/com.visualstudio.code/issues/370

# Solution:
- works: https://github.com/flathub/com.visualstudio.code/issues/370#issuecomment-1666515496

>My settings.json
>```
>"terminal.integrated.env.linux": {
>  "LD_PRELOAD": null,
>},
>```

## Relation: settings.json
- sch: https://www.google.com/search?q=vscode+settings.json
- https://stackoverflow.com/questions/65908987/how-to-open-visual-studio-codes-settings-json-file

## discuss:
- https://www.reddit.com/r/Fedora/comments/14cezl0/getting_vs_codium_setup_properly_with_flatpak/
- https://github.com/orgs/ublue-os/discussions/155#discussioncomment-6025057
