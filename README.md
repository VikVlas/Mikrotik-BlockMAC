# Mikrotik-BlockMAC
Блокировка по МАС согласно анализу логов

Скрипт, который анализирует логи Mikrotik. Если попадается сообщение о подключении с неправильным паролем - добавляется правило в access-list, которое запрещает данному клиенту (по MAC) подключатся к всем нашим беспроводным интерфейсам
Скрипт в планировщик с запуском каждые N минут. Для того, чтобы в бан не попадали разрешённые устройства - заранее добавляем их в Access List.
