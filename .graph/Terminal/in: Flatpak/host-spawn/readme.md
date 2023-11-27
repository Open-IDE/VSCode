Use this settings.json file to let VS Code in a Flatpack have access to Host environment's $PATH! For ex. `which ansible`

path: "{{ ansible_env.HOME }}/.var/app/com.visualstudio.code/config/Code/User/settings.json"
