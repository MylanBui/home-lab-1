# Home Lab

A self-hosted home server for photo backup and file storage, built incrementally as a learning project.

## Project Goal

Store all my photos, files, and data on a server I control instead of paying for cloud subscriptions like iCloud, Google Drive, and Snapchat storage.


## Tech Stack

- **Hardware**: M1 MacBook Air + 2TB external SSD
- **Server Software**: Docker, Immich, Nextcloud
- **Networking**: Tailscale, Nginx
- **Languages**: Bash, Python, JavaScript (as needed)

## Learning Resources

- [Docker Documentation](https://docs.docker.com/)
- [Immich GitHub](https://github.com/immich-app/immich)
- [Nextcloud Documentation](https://docs.nextcloud.com/)
- [Tailscale Guide](https://tailscale.com/kb/)

## Phases

### Phase 1: Get It Running


- Set up Docker on M1 MacBook Air
- Install and configure Immich for photo backup
- Install and configure Nextcloud for file storage
- Connect phone to Immich for automatic photo sync

### Phase 2: Make It Accessible

- Set up Tailscale for remote access
- Configure Nginx reverse proxy
- Learn networking and security basics

### Phase 3: Start Coding
- Write shell scripts for automated backups
- Build storage monitoring and alerts
- Create a simple status dashboard

### Phase 4: Go Deeper
- Build a REST API layer
- Add database indexing and search
- Implement automated photo organization



## Progress

Currently in setup phase. Waiting for hardware to arrive.

## Phase 1: Docker Basics

Learned that Docker isolates software in containers. Each container runs independently so updates and crashes don't affect other services. Installed Docker and confirmed it works with `docker --version` and `docker run hello-world`.


