# Implementando un stack de monitorización basado en Icinga2

Mediante el uso de Ansible se procederá a implementar de forma automatizada un stack de monitorización con los siguientes softwares en un sistema operativo Ubuntu Server 18.04: 

* **Icinga2**
* **Icingaweb2**
* **InfluxDB**
* **Grafana**

Para su implementación se hará uso de los siguientes roles:

* **system** -> (opcional) Configuración básica del sistema servidor.
* **icinga2** -> Instalación y configuración del software de monitorización Icinga2.
* **icingaweb2** -> Instalación y configuración de Icingaweb2 para la visualización gráfica de Icinga2.
* **graphing** -> Instalacón y configuración de InfluxDB y Grafana para la creación y visualización de gráficas.
