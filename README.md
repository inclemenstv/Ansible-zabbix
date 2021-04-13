Как использовать.
=========
1. Указать версию для обновления zabbix для этого изменить значение переменной zabbix_version в файле /defaults/main.yml :

         zabbix_version: 5.2

2. Указать путь для бекапа базы и файлов для этого изменить значение переменной zabbix_backup_folder в файле /defaults/main.yml :

        zabbix_backup_folder: /opt/zabbix-backup
    
3. Добавить роль в ваш плейбук.
        
        roles:
        - zabbix_update
