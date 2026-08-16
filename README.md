## Установка сертификатов Hysteria2 для RemnaNode
```bash
curl -fsSL https://raw.githubusercontent.com/benzin98support-lgtm/scripts/main/remnanode-hysteria2-certbot -o remnanode-hysteria2-certbot && chmod +x remnanode-hysteria2-certbot && sudo ./remnanode-hysteria2-certbot
```
Потребуется указать: домен ноды, email для Let's Encrypt, `SECRET_KEY` ноды.

## Установка ноды без сертификата (Reality)
```bash
curl -fsSL https://raw.githubusercontent.com/benzin98support-lgtm/scripts/main/remnanode-no-cert -o remnanode-no-cert && chmod +x remnanode-no-cert && sudo ./remnanode-no-cert
```
Потребуется указать: `SECRET_KEY` ноды.
