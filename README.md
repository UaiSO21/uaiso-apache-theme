# uaiso-apache-theme
Tema padrão para o idexes do Apache com .htaccess

## Separar o diretório "assets":
### /etc/apache2/mods-enabled/alias.conf
```
        Alias /assets "/usr/share/apache2/assets/"

        <Directory "/usr/share/apache2/assets">
                Options FollowSymlinks
                AllowOverride None
                Require all granted
        </Directory>
```
Obtido [desta página no StackExchange](https://serverfault.com/a/848675)