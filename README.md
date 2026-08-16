## Установка ноды Remnawave без сертификата (Reality)
Запустите команду на сервере:
```bash
curl -fsSL https://raw.githubusercontent.com/benzin98support-lgtm/scripts/main/remnanode-no-cert -o remnanode-no-cert && chmod +x remnanode-no-cert && sudo ./remnanode-no-cert
```
Во время установки потребуется указать:
- `SECRET_KEY` ноды из панели Remnawave

После завершения контейнер ноды будет запущен без выпуска сертификата — подходит для инбаундов, которым не нужен свой домен/TLS (например Reality).
