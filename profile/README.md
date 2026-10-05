# Kit móvil de atención primaria en salud

Proyecto final de **Plataformas I (2026-2) - Universidad Icesi**. Es una plataforma modular y portátil que presta servicios digitales de salud y conectividad comunitaria, y que sigue operando aunque no haya Internet. Un mini PC hace de router/firewall y aloja dos VMs: una clínica y otra comunitaria.

| Repositorio | Contenido |
|---|---|
| [`docs`](https://github.com/kitsalud-movil-plats1/docs) | Arquitectura, decisiones, diagramas, guías de despliegue y operación, evidencias |
| [`network`](https://github.com/kitsalud-movil-plats1/network) | Red de kit01 (nftables, Kea, radvd, portal cautivo), switch y AP |
| [`platform`](https://github.com/kitsalud-movil-plats1/platform) | Base de kit01 (KVM, DNS, NTP, NUT, NetBird), Samba AD, backups, Ansible |
| [`apps`](https://github.com/kitsalud-movil-plats1/apps) | DHIS2, consulta de formularios, biblioteca Kiwix, videos Jellyfin, formularios de prerregistro |
| [`observability`](https://github.com/kitsalud-movil-plats1/observability) | Prometheus, Grafana, logs centralizados (rsyslog) |

Punto de partida: `docs/arquitectura/00-punto-de-partida.md`.
