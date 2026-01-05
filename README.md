# wazuh-home-lab
Despligue de SIEM Wazuh para monitoreo y seguridad de red doméstica.

## Arquitectura del Laboratorio

El laboratorio se diseñó bajo una arquitectura híbrida para simular un entorno empresarial real, permitiendo la comunicación entre activos físicos y virtuales.

- **Servidor SIEM (Wazuh Manager):** - OS: Ubuntu Server 22.04 LTS
  - IP: 192.168.100.50 (Estática via Netplan)
  - Rol: Indexación de logs, gestión de alertas y servidor de políticas.
- **Estación de Gestión:** - OS: Debian 12 (Laptop Física)
  - Conectividad: Acceso remoto seguro mediante SSH.
- **Red:** - Configuración: Adaptador Puente (Bridged) para visibilidad total en la LAN doméstica.
