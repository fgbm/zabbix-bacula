zabbix-bacula
===
Мониторинг системы резервного копирования Bacula для Zabbix

Русерсы/метрики/триггеры
===
* Auto Discovery JOBS (lld discovery)
* JOB status (item)
* JOB elapsed time (item/graph) by FULL/INCREMENTAL/DIFFERENTIAL 
* JOB size (item/graph) by FULL/INCREMENTAL/DIFFERENTIAL
* Backup doesnt OK (trigger)
* Backup doesnt executed at last 24 hours (trigger)
* Backup status doesnt received at last 6h (trigger)


Установка
===
* скопировать zabbix-sudo в /etc/sudoers.d/
* скопировать conf/Bacula.conf в /etc/zabbix/zabbix.agent.d/
* скопировать scripts/ в /etc/zabbix/scripts
* импортировать шаблон (templates/zbx_export_templates.xml)

Автор
=====
* Fábio Miguel Mello

