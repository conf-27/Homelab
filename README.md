# Homelab

Configurazione iniziale di un homelab ad un solo nodo

```mermaid
graph TD
    Internet --> Router
    Router --> Nodo1
    Router --> mainArch
    Nodo1 --> NFS
    Nodo1 --> Docker
```

