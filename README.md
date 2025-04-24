# r002-ansible
Автоматизация создания сайта на Ansible для проекта r001-lemp на сервере, параметры связи с которым в файле hosts.ini.
Для роли mysqlinstall имеется зашифрованный файл mysqlinstall/vars/main.yml, в котором есть параметры:
---------------------------------
root_password: 
admin_user: 
admin_password: 
db_name: expo
password_validation_policy: 1
---------------------------------
Поэтому для запуска плейбука нужен пароль. 
Используется php8.1 (могут быть накладки).
