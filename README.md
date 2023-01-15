# uaiso-apache-theme
Tema padrão para o idexes do Apache com .htaccess

## Incluir "assets" fora do DocumentRoot
- Modifique o arquivo `/etc/httpd/conf/httpd.conf`
- No módulo alias_module, insira a linha:
```
Alias /assets "/opt/uaiso-apache-theme/assets/"
```