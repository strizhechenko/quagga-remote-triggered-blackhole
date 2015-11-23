# quagga-remote-triggered-blackhole

Пытаемся настроить рабочую связку для RTBH (remote triggered blackhole) из ExaBGP (анонсер) и Quagga (бордер)

# IP адреса

- Бордер
  - 10.90.140.230 - ip через который он дружит с анонсером
  - 10.30.30.1 - ip к локалке с пользователями
- Анонсер
  - 10.90.140.130 - ip через который он дружит с бордером
  - 10.30.31.1 - ip к локалке, не очень важно
- Жертвы
  - 10.10.10.1 - первая жертва, которую надо отправить в blackhole на бордере
- Остальное
  - 192.0.2.1 - ip блэкхола
