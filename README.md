
# Portainer V2 Templates for Selfhosted Projects/Homelabs

This is a template focused on helping people spin up selfhosted services using Portainer.


### Prerequisites

1. A server/NAS with docker installed
2. A Portainer setup.


### Installing

1. Login to your portainer setup go to settings
2. Enable Use external templates
3. Add the url: `https://raw.githubusercontent.com/eidanyosoy/portainer_templates/master/Template/template.json` then go to app templates and hit refresh at the top.

### Information
All templates are already configured to bind mount to various places on your drive. This branch is being worked on for deployment in conjunction with Dockserver. The following folders are all created 
* **Files** - General file storage.
  * **appdata** - Subfolder where application data (unrelated to served data) is stored.
    * **config** - Subfolder where configuration files for every container are stored.
* **downloads** - Where bittorrent and usenet downloaders download files to.
* **tv** - Where tv shows are stored/moved to after downloaded.
* **movies** - Where movies are stored/moved to after downloaded.
* **music** - Where music is stored/moved to after downloaded.
* **books** - Where books are stored/moved to after downloaded.
* **comics** - Where comics are stored/moved to after downloaded.
* **podcasts** - Where podcasts are stored/moved to after downloaded.

## App List

  - Adguard 
  - Airsonic 
  - Authelia 
  - Bazarr 
  - Beets 
  - Vaultwarden 
  - Booksonic 
  - Cops 
  - Calibre-web 
  - Chevereto 
  - Chowdown 
  - Code-server 
  - Codiad 
  - Couchpotato 
  - Daapd 
  - Dashmachine 
  - Davos 
  - Deemix 
  - Domoticz 
  - Duckdns 
  - Duplicati 
  - Emby 
  - EmbyStat 
  - Filebrowser 
  - Freshrss 
  - Gazee 
  - Guacamole 
  - Grocy 
  - Htpcmanager 
  - Headphones 
  - Heimdall 
  - Homer 
  - Huginn 
  - Invoice_ninja 
  - Jackett 
  - Jellyfin 
  - kodi-headless 
  - Lazylibrarian 
  - Letsencrypt / SWAG 
  - Librespeed 
  - Lidarr 
  - Lychee
  - Mariadb 
  - Mcmyadmin2 
  - Medusa 
  - Minetest 
  - Minisatip 
  - Mstream 
  - Murmur 
  - Musicbrainz 
  - Muximux 
  - Mylar 
  - Nzbget 
  - Nzbhydra2 
  - Nextcloud 
  - Nginx 
  - Nginx-proxy-manager 
  - Oscam 
  - Ombi 
  - Openvpn-as 
  - Organizr-v2 
  - Overseerr 
  - Owncloud 
  - Petio 
  - Photoshow 
  - Pihole 
  - Piwigo 
  - Plex 
  - Plexrequests 
  - Projectsend 
  - Protonmail-bridge 
  - Prowlarr 
  - Pydio 
  - Qbittorrent 
  - Quassel-core 
  - Radarr 
  - Reactive-resume 
  - Resilio-sync 
  - Rutorrent 
  - Sabnzbd 
  - Shiori 
  - Sickchill 
  - Sickgear 
  - Smokeping 
  - Snibox 
  - Sonarr 
  - Syncthing 
  - Tautulli 
  - Thelounge 
  - Tiddlywiki 
  - Tt-rss 
  - Transmission 
  - Transmission-openvpn 
  - Tvheadend 
  - Ubooquity 
  - Unifi-controller 
  - Watchtower 
  - Webgrabplus 
  - Whoogle 
  - Wikijs 
  - Yacht 
  - Youtubedl-material 
  - Znc 

## Authors
* **eidanyosoy** - *Current Work* - [eidanyosoy](https://github.com/eidanyosoy)
* **NASHosted** - *Initial work*  - [NASHOSTED](https://github.com/nashosted)
* **SelfhostedPro** -  *Initial work* [SelfhostedPro](https://github.com/SelfhostedPro)
* **Jos Visser** - *Initial work* - [Qballjos](https://github.com/Qballjos)
* **xe-nvdk** - *template conversion to portainer V2* - [xe-nvdk](https://github.com/xe-nvdk)
* **tbiering** - *Termplate cleanup and typo fixes* - [tbiering](https://github.com/tbiering)

See also the list of [contributors](https://github.com/Qballjos/portainer_templates/graphs/contributors) who participated in this project.

## Acknowledgments

* LinuxServer.io for the old Template
* Inspiration being too lazy to create each container template manualy
* The team behind Portainer for there awesome product and support in the community
