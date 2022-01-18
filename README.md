### Homelab k8s Deployments

| Name | Image | External Port | Container Port |
| --- | --- | --- | --- |
| Gitea | gitea/gitea:latest | 3000 | 3000 |
| Nginx | nginx:1.16.0-alpine | 3999, 4000 | 80, 443 |
| Pihole | pihole/pihole:latest | 8000, 53/tcp, 53/udp | 80, 53/tcp, 53/udp |
| Transmission | ghcr.io/linuxserver/transmission | 9091, 51413/tcp, 51413/udp | 9091, 51413/tcp, 51413/udp |
| Unbound | mvance/unbound:latest | 5353/tcp, 5353/udp | 53/tcp, 53/udp |
| Rss-producer | docker.io/galleywest/rss-producer | 5000 | 5000 |