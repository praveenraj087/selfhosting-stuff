# Self-Hosted Media Server Stack

This is my not-so-fully automated media server stack. It is supposed to make me spend less on subscriptions but i've spent way too much on hard drives already to offset that (smh), also supposed to be self-sufficient to an extent and scalable but let's see lol.

## What I've done so far
* **The Arrs**: Radarr, Sonarr for procurement of "data"
* **Ingest Engine**: Uses qBittorrent and Usenet indexers tied together with Prowlarr, and routed thorough a Glutun Wireguard VPN Container.
* **Hardware Transcoding**: Tdarr is configured with Nvidia GPU passthrough to rapidly shrink media files to H.265.
* **Quality Control**: Profilarr is set up to automatically enforce Dictionarry rules for all downloads.
* **Remote Requests and Alerts**: Fully integrated with Seerr, Icarus and ntfy.sh for real-time mobile requests and download notifications.
* **Pi-Hole**: Network-wide ad-blocker with custom blocklists.
* **Portainer**: Container Management Tool.
* **Uptime-Kuma**: Added to monitor container up-time and health remotely integrated with ntfy.
  
## Things I'm Working On
* **Bazarr:** To fully automate subtitle downloading and synchronization for the media library.
* **Homepage Dashboard:** Building out a unified landing page (currently deciding between configuring my existing Glance container or switching to Homepage).
* **Immich:** Setting up a self-hosted Google Photos alternative for mobile backup.
* ~~**Pi-hole**~~
* ~~**Portainer:*~~
* ~~**Uptime Monitor**~~


