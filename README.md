# Laboratorio de Ciberseguridad, Redes y DevOps

Soy Diego Artavia, estudiante de Ingeniería en Informática en la Universidad Latinoamericana de Ciencia y Tecnología (ULACIT), Costa Rica. Este repositorio documenta el diseño, despliegue y endurecimiento (Hardening) de mi laboratorio de infraestructura local sobre una Raspberry Pi 5. 

El objetivo de este entorno es servir como un banco de pruebas controlado para estudiar arquitecturas de red, gestión de vulnerabilidades y despliegue de microservicios.

---

## Estado del Laboratorio y Hoja de Ruta

### Fase 1: Infraestructura Base y Redes
- [x] Configuración de Raspberry Pi OS y montaje de almacenamiento SSD Gigastone.
- [x] Orquestación de contenedores Docker mediante CasaOS.
- [x] Acceso remoto seguro mediante Tailscale (Arquitectura Zero-Trust).

### Fase 2: Auditoría, Monitoreo y Domótica Local
- [X] Mapeo de superficie de ataque y auditorías perimetrales de puertos locales con Nmap.
- [X] Despliegue de Uptime Kuma para observabilidad de red y telemetría de hardware.
- [X] Centralización de IoT local mediante Home Assistant (Integración de dispositivos Bluetooth BLE).

### Fase 3: Seguridad de Red Avanzada
- [ ] Implementación de un Resolver DNS recursivo (Unbound + Pi-hole) para validación DNSSEC y mitigación de DNS Spoofing.
- [ ] Inspección de tráfico y captura de paquetes mediante Wireshark.
- [ ] Levantamiento de un túnel VPN crudo utilizando el protocolo WireGuard puro (sin abstracciones).
- [ ] Auditoría de redes inalámbricas y túneles inversos (Chaffing de red).

### Fase 4: Ciberseguridad Defensiva y SOC (Security Operations Center)
- [ ] Despliegue de un SIEM (Security Information and Event Management) personal mediante Wazuh para correlación de eventos.
- [ ] Sistema de Detección de Intrusos (IDS) perimetral utilizando Suricata.
- [ ] Implementación de Honeypots para análisis de vectores de ataque y reconocimiento de amenazas.
- [ ] Escáner de vulnerabilidades automatizado utilizando OpenVAS / Greenbone.
- [ ] Servidor de auditoría y ruptura de contraseñas por fuerza bruta controlada.

### Fase 5: Microservicios, IA y Criptografía Aplicada
- [ ] Orquestación de contenedores de alta disponibilidad mediante Kubernetes liviano (K3s Multi-Nodo).
- [ ] Despliegue de Modelos de Lenguaje Locales (Private LLM / IA Local) mediante Ollama.
- [ ] Nodo de computación cifrada utilizando Criptografía Homomórfica (FHE).
- [ ] Servidor de almacenamiento inmutable y auditoría forense sobre Blockchain privada.
- [ ] Estación de recepción de satélites de órbita baja mediante SDR (Software Defined Radio).

---

## Stack Tecnológico Utilizado
* **Hardware:** Raspberry Pi 5 (8GB RAM) + SSD NVMe Gigastone.
* **Sistema Operativo:** Raspberry Pi OS (Debian 12 Bookworm de 64-bits).
* **Gestión de Aplicaciones y Redes:** Docker Engine, CasaOS, OpenSSH, Tailscale.

---



---
Contacto Profesional: https://www.linkedin.com/in/diego-artavia-valverde , diartavia@gmail.com

