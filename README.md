# Homelab

Configurazione iniziale di un homelab ad un solo nodo

```mermaid
graph TD
    Internet --> Router
    Router --> server1
    Router --> mainArch
    server1 --> NFS
    server1 --> Docker
    Docker --> Beszel
    Docker --> Immich
```

