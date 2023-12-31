## Задание: Настройка сетевой инфраструктуры для малого офиса.

Для выполнения задания используйте дистрибутив [pfsense](https://www.pfsense.org/download/)

1. Подготовьте диаграмму сети для малого офиса, включающую следующие компоненты: маршрутизатор, коммутаторы, сервера, рабочие станции.

2. Настройте маску подсети для каждого сегмента сети в соответствии с требованиями офиса.

3. Разработайте и реализуйте модель OSI для вашей сети, учитывая все семь уровней модели.

4. Настройте статический роутинг между основными сегментами сети. Укажите маршруты для обмена трафиком между сегментами.

5. Реализуйте динамический роутинг с использованием протокола OSPF для автоматического обнаружения маршрутов между подсетями.

6. Настройте VLANы для различных отделов в офисе. Укажите соответствующие порты на коммутаторах.

7. Создайте туннель VPN между двумя удаленными офисами с использованием IPSEC для безопасного обмена данными.

8. Настройте NAT на маршрутизаторе для обеспечения доступа к интернету для всех устройств в сети.

9. Создайте и примените списки контроля доступа (ACL) для ограничения трафика в сети, например, для блокировки определенных портов или IP-адресов.

10. Настройте сервер NTP, чтобы обеспечить синхронизацию времени для всех устройств в сети.

11. Реализуйте протокол VRRP для обеспечения отказоустойчивости для маршрутизатора в случае его сбоя.

12. Настройте систему тайминга для управления синхронизацией внутреннего времени маршрутизатора и других устройств в сети.

13. Настройте DHCP сервер для автоматической выдачи IP-адресов и других настроек сети рабочим станциям. Обратите внимание на использование helper-устройств для пересылки DHCP-запросов.

14. Создайте и настройте DNS сервер, чтобы обеспечить резолвинг доменных имен внутри сети.

15. Настройте Firewall для защиты сети от внешних атак. Правильно настройте правила фильтрации, чтобы разрешить только нужный сетевой трафик.

16. Реализуйте QoS для управления пропускной 