
# seedbox
Seedbox Complete sous docker d'après le script de https://github.com/ayu69/seedbox


## installation

    apt update && apt upgrade
    apt install git
    cd /tmp
    git clone https://github.com/ayu69/seedbox.git
    cd seedbox
    mv seedbox.sh logo.sh /usr/local/bin
    mv iptables /etc/iptables
    cd /usr/local/bin
    chmod +x seedbox.sh logo.sh
    seedbox.sh


Plus d'infos :
https://mondedie.fr/d/5318-Tuto-Securisation-Logs-V-3-nginx
https://mondedie.fr/



 - traefik
 - rtorrent
 - plex
 - sonarr
 - radarr
 - tautulli
 - filebot
 - nextcloud
 - heimdall
 - portainer
 - jackett
 - Syncthing
 - lidarr
 - ombi
