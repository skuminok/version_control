# Как включить ssh в Windows 10

В ОС Windows 10 по умолчанию уже есть ssh. Его надо только активировать.

Зайдите в Параметры - Приложения - Приложения и возможности - Дополнительные компоненты. В указанном спсике найдите **Клиент OpenSSH**, жмите установить.

Откройте cmd.

Наберите команду: 

```sh
C:\Users\USER\> ssh
usage: ssh [-46AaCfGgKkMNnqsTtVvXxYy] [-B bind_interface]
           [-b bind_address] [-c cipher_spec] [-D [bind_address:]port]
           [-E log_file] [-e escape_char] [-F configfile] [-I pkcs11]
           [-i identity_file] [-J [user@]host[:port]] [-L address]
           [-l login_name] [-m mac_spec] [-O ctl_cmd] [-o option] [-p port]
           [-Q query_option] [-R address] [-S ctl_path] [-W host:port]
           [-w local_tun[:remote_tun]] destination [command]
```

Перейдите к созданию ssh ключа.
