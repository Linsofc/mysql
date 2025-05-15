# Mysql Error Connect
1. Buka Xampp -> shell
    ```bash
    mysqld --console --skip-grant-tables --skip-external-locking

2. buka shell baru
    ```bash
    mysqlcheck -r --databases mysql --use-frm

3. jika sudah close semua shell 2 dan 1