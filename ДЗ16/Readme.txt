# Lab №16. Bacula backup
# Vagrantfile - конфигурация vagrant для разворачивание двух серверов: bacula и client 
# bacula-dir.conf, bacula-sd.conf, bacula-fd.conf - конфигурация сервисов (Director, Storage и FileDaemon) на бэкап-сервере bacula
# client-fd.conf - конфигурация FileDaemon на клиентском сервере client
# List Jobs.txt - вывод команды "list jobs" через bconsole на сервере bacula
# List Files.txt - вывод команды "list files jobid=56" через bconsole на сервере bacula