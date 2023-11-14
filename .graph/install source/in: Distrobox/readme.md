Separate Home folder:
```
createDistrobox(){
  to=~/.uni/container/distrobox/dev.fedora; mkdir -p $to; distrobox create --image fedora:39 --name dev.fedora --home $to  
}

enter(){
  distrobox enter dev.fedora
}

install(){
  sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
  sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'
  dnf check-update
  sudo dnf install code
  # from: https://code.visualstudio.com/docs/setup/linux
}

export(){
  distrobox-export --app code
}
```
