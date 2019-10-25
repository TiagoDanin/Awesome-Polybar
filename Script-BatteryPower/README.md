# Script Battery-Power


# Dependencies
`pwrstat` 

# Configuration


`user ALL=(ALL) NOPASSWD: /usr/bin/pwrstat`

`Module
[module/battery-cyberpower]`

`type = custom/script`

`exec = ~/polybar-scripts/battery-cyberpower.sh`

`tail = true`
