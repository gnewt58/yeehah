## Zabbix
Zabbix is an open source monitoring software tool for diverse IT components, including networks, servers, virtual machines (VMs)
and cloud services. Zabbix provides monitoring metrics, among others network utilization, CPU load and disk space consumption.
Zabbix monitoring configuration can be done using XML based templates which contains elements to monitor. The software monitors
operations on Linux, Hewlett Packard Unix (HP-UX), Mac OS X, Solaris and other operating systems (OSes); however, Windows 
monitoring is only possible through agents. Zabbix can use MySQL, MariaDB, PostgreSQL, SQLite, Oracle or IBM DB2 to store data.
Its backend is written in C and the web frontend is written in PHP.

#### Changelog

##### v0.1.0
* Initial version, based on [monitoringartist/zabbix-xxl](https://hub.docker.com/r/monitoringartist/zabbix-xxl/)

#### Usage

##### Setup
After deploying, launch the WEBUI and supply the database credentials.

##### Default Credentials
After deployment, use the default credentials of admin/password, to log into zabbix. 
