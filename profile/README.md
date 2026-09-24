# Kit móvil de atención primaria en salud

Proyecto final de **Plataformas I (2026-2) - Universidad Icesi**. Es una plataforma modular y portátil que presta servicios digitales de salud y conectividad comunitaria, y que sigue operando aunque no haya Internet.

| Repositorio | Contenido |
|---|---|
| [`docs`](https://github.com/kitsalud-movil-plats1/docs) | Arquitectura, decisiones, diagramas, guías de despliegue y operación, evidencias |
| [`network`](https://github.com/kitsalud-movil-plats1/network) | OPNsense (firewall, VLAN, DHCP, portal cautivo), switch y AP |
| [`platform`](https://github.com/kitsalud-movil-plats1/platform) | Hipervisor KVM, DNS (BIND9), NTP (Chrony), Samba AD, almacenamiento, backups, Ansible |
| [`apps`](https://github.com/kitsalud-movil-plats1/apps) | DHIS2, biblioteca Kiwix, formularios de prerregistro, reverse proxy |
| [`observability`](https://github.com/kitsalud-movil-plats1/observability) | Prometheus, Grafana, Loki, alertas |

Punto de partida: `docs/arquitectura/00-punto-de-partida.md`.
