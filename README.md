# 📡 Monitoreo de Redes y Sistemas – DTES-ULA

Repositorio dedicado al despliegue, configuración, automatización y documentación de soluciones de monitoreo para infraestructuras de red y sistemas críticos.

## 🛠 Stack tecnológico

| Categoría            | Herramientas                                                                 |
|----------------------|------------------------------------------------------------------------------|
| **Métricas y alertas** | Zabbix, Icinga, Nagios                                                       |
| **Tráfico de red**     | NtopNG, SmokePing                                                           |
| **Logs y SIEM**        | Elasticsearch, Wazuh                                                        |
| **Visualización**      | Grafana, Observium                                                          |

## 📁 Estructura del repositorio
monitoreo-redes/
├── zabbix/ # Templates, scripts y configuración de Zabbix
├── icinga/ # Configuración de Icinga2, check commands
├── nagios/ # Configuración de Nagios Core / XI
├── ntopng/ # Reglas de monitoreo de tráfico y alertas
├── smokeping/ # Probes, targets y gráficas de latencia
├── observium/ # Configuración de community strings, dispositivos
├── wazuh/ # Reglas personalizadas, decoders, integración con Elastic
├── elasticsearch/ # Pipelines, índices, dashboards (Kibana)
├── grafana/ # Dashboards exportados, datasources, alertas
└── docs/ # Guías de instalación, arquitectura, troubleshooting


## 🚀 Propósito

- Centralizar configuraciones probadas para entornos de red reales / académicos
- Automatizar la detección de anomalías (latencia, ancho de banda, caídas de servicio, eventos de seguridad)
- Proveer dashboards reutilizables y documentación técnica actualizada
- Integrar monitoreo clásico (Nagios, Icinga) con stacks modernos (ELK, Wazuh)

## 📊 Ejemplo de métricas monitoreadas

- Disponibilidad (`ping`, `http`, `tcp`, `dns`)
- Ancho de banda y flujos (`NetFlow/sFlow`, `SNMP`, `ntopng`)
- Latencia (`SmokePing`, `fping`)
- Logs de seguridad (`Wazuh` + `Elasticsearch`)
- Métricas de sistema (`CPU`, `RAM`, `disco`, `procesos`)

## 👥 Mantenedores

- **DTES-ULA** – Grupo de Desarrollo Tecnológico en Electrónica y Sistemas, Universidad de Los Andes, Venezuela

## 📄 Licencia

MIT – Libre para uso educativo y profesional

---

🌐 **Repositorio:** `https://github.com/monitoreoula/monitoreo-redes`
