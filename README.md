# ru-blocklist-adguard

Список для AdGuard Home: блокирует зоны `.ru`, `.su`, `.рф`, `.рус`, `.москва`, `.moscow`
и домены российских сервисов на других TLD (yandex.*, ozon.*, wildberries.*, vk.*, tinkoff.* и т.д.).

Подписка: Filters → DNS blocklists → Add a blocklist → Add a custom list

    https://raw.githubusercontent.com/s3ths1/ru-blocklist-adguard/main/ru-blocklist-adguard.txt

Правила вида `||domain^` блокируют домен и все его поддомены.
Исключения (например, зеркала пакетов) добавляй в Custom filtering rules: `@@||mirror.yandex.ru^`.
