# SEEDBOX INSTALL SCRIPT
Easily install [Plex](https://github.com/plexinc/plex-media-player), [Sonarr](https://github.com/Sonarr/Sonarr), [Radarr](https://github.com/Radarr/Radarr), [Deluge](https://github.com/deluge-torrent/deluge) and [Jackett](https://github.com/Jackett/Jackett) with one script!  

## Install  
`wget https://raw.githubusercontent.com/Tvax/seedbox-install/master/vpsInitscript.sh;`  
`chmod 755 vpsInitscript.sh`  
`./vpsInitscript.sh;`  

## Plex
To install Plex via SSH :  
`ssh USER@IP -L 8888:localhost:32400`  
Then open your browser on :  
`localhost:8888`  
To mount a network drive that Plex can use :  
`sudo sshfs -o allow_other,default_permissions USER@IP:/Plex /Plex`  

## Deluge
Connect to Deluge :  
`IP:8112`  
Default password :  
`deluge`  
For more help :  
1. https://docs.google.com/document/d/1cARrPUryp-X37QZy29hCMA3zVddDCg4NmBCIZEflel8/edit
2. http://dev.deluge-torrent.org/wiki/UserGuide/ThinClient#WebUI

## Sonarr
Connect to Sonarr :  
`IP:8989`  

## Radarr
Connect to Sonarr :  
`IP:7878`  
For more help :  
1. https://www.htpcguides.com/install-radarr-on-debian-8-jessie/  

## Jackett
Connect to Jackett :  
`IP:9117`  
