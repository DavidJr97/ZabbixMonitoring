# Información

Monitoreo de Hardware y servicios mediante Zabbix-Docker.

# DESCARGAR REPOSITORIO E INSTALAR
    1. Instalar mediante docker-compose el archivo docker-compose.yml para instalar Zabbix y Grafana.

# CONFIGURAR ZABBIX AGENT
1. Ver IP del agente mediante docker inspect [ID_Image]
2. remplazar la IP por default en las configuraciones de Zabbix Server.

# CONTRASEÑA PARA INGRESAR A ZABBIX 
1. Zabbix (Admin zabbix)
2. Grafana (admin admin)

# GRAFANA CONFIGURATION
1. Download Plugin zabbix on Configuration.

## Mysql
1. Host: localhost:3306
2. Database: zabbix
3. User: zabbix
4. Password: carryontech

## Zabbix pluggin in Grafana
1. URL: http://localhost/api_jsonrpc.php
2. User: Admin
3. Password: zabbix

# REFERENCES 
1. [Docker + System dashboard](https://grafana.com/grafana/dashboards/893)
2. [Grafana](https://grafana.com/grafana/dashboards/893)
3. [Zabbix agent for windows](https://www.zabbix.com/la/download_agents?version=5.2&release=5.2.2&os=Windows&os_version=Any&hardware=amd64&encryption=OpenSSL&packaging=MSI)
4. [Zabbix Monitorear Linux utilizando el Agente](https://techexpert.tips/es/zabbix-es/zabbix-monitor-linux-usando-agent/)
5. [Zabbix Monitorear Windows utilizando SNMP](https://techexpert.tips/es/zabbix-es/zabbix-monitor-windows-usando-snmp/)
6. [Zabbix Monitorear Oracle utilizando Agente](https://www.zabbix.com/la/integrations/oracle)
7. [Zabbix Monitorear Docker utilizando Agente](https://techexpert.tips/es/zabbix-es/supervision-de-docker-mediante-zabbix/)
8. [Notificaciones Mediante Correo Electrónico](https://techexpert.tips/es/zabbix-es/zabbix-configuracion-de-notificacion-por-correo-electronico/)