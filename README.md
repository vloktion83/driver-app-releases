# OptiRoute Водитель — Android releases

Публичный binary-only канал обновлений приложения **OptiRoute Водитель**.

Здесь публикуются только:

- подписанный APK;
- точный companion-файл `<apk>.sha256`;
- `release-manifest.json` и `latest.json`;
- русский changelog.

Исходный код, production keystore, секреты подписи и R8 mapping находятся вне этого публичного репозитория.

Приложение перед установкой проверяет HTTPS, SHA-256, package ID, увеличение `versionCode` и совпадение сертификата подписи. Если integrity metadata отсутствуют или повреждены, прямая установка отключается.

Первый APK будет опубликован после live-canary мобильного API и настройки production-подписи.