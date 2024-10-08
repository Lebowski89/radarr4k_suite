Radarr4K Suite
=========

    Standalone Ansible role to automate the full set-up of Radarr4K - a 4K (3840 x 2160 pixel) movie collection manager for Usenet and BitTorrent users.
      - Includes the installation of Docker (Debian-based distros) and Ansible dependencies within the role.
      - Includes the option of setting up and connecting Radarr4K to a Postgres database.
      - Includes the option of setting up Prometheus and a Radarr4K Promtheus exporter to gather various metrics about your Radarr4K usage and music collection.
      - Includes the option of creating a Cloudflare DNS record for your Radarr4K instance for reverse proxy purposes.
      - Includes the option of setting up Autofs NFS (to provide media access on the host system) and Docker NFS volumes (to attach to the Radarr4K container).
      - Includes the option of setting up the Rclone Docker plugin and the creation of Rclone Docker volumes (to attach to the Radarr4K container).
      - Includes the option of joining Radarr4K to an existing Traefik docker network (or creating one if none exists).
      - Includes the option of editing Radarr4K's config.xml to include an existing Radarr4K API - maintaining connections to other applications that rely on it.

(Proper documentation is coming...)
