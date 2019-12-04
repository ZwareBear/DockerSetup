# DockerSetup
This repo contains files I've used to setup my personal docker setup, used for my home media library.

Containers used:

  Tautulli - Plexstats page

  Ombi - used for requesting new media 

  nzbget - downloader, usenet

  sonarr - manager, monitors tv shows

  radarr - manager, monitors movies

  jackett - indexer, used to add sites for sonarr/ radarr

  arch-deluge - downloader, uses deluge behind an openvpn connection

  portainer - GUI for managing docker containers
  
  traefik - reverse proxy, used to host multiple services on one domain
  
  fail2ban - ban ips after so many failed attempts
  
  influxdb - data analytics, real-time database for system information
  
  grafana - data analytics, dashboard for viewing data from influxdb
  
  telegraf - data analytics, used for feeding docker info into influxdb
