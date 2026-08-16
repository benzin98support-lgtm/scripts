## Установка сертификатов Hysteria2 для RemnaNode

Запустите команду на сервере:

```bash
curl -fsSL https://raw.githubusercontent.com/benzin98support-lgtm/scripts/main/remnanode-hysteria2-certbot -o remnanode-hysteria2-certbot && chmod +x remnanode-hysteria2-certbot && sudo ./remnanode-hysteria2-certbot
```

Во время установки потребуется указать:

- Домен ноды
- Email для Let's Encrypt
- `SECRET_KEY` ноды из панели Remnawave

После завершения сертификаты для Hysteria2 будут выпущены и настроены автоматически.
