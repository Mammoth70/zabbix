## Шаблоны Zabbix
 
### шаблон Zabbix 5 для криптошлюзов Континент 3.9
**zbx_continent3_templates.xml**

автозаполнение полей инвентаризации;  

триггеры ICMP-ответа (по умолчанию отключено);  
графики и триггеры загрузки процессора, памяти, swap-файла и дисков;  
графики и триггеры загрузки, разных событий и ошибок на сетевых интерфейсах;  
комплексный экран графиков всех сетевых интерфейсов;  
триггеры ввода в эксплуатацию и мягкого режима;  
триггеры изменения версии сборки, перезапуска устройства и перезапуска сетевой системы;  
триггер рассинхронизации времени;  
триггер периодичности подключения к ЦУС;  
триггеры истечения срока действия ключей;  
триггеры падения VPN, ошибок на VPN (по умолчанию включено только для 5-го приоритета);  

автоматическое определение наличия сервера доступа на криптошлюзе;  
для сервера доступа график количества подключений;  
для сервера доступа триггер недостаточности свободных лицензий;  
для сервера доступа триггеры истечения срока действия сертификатов.  

### шаблон Zabbix 5 для криптошлюзов Континент 4.1
**zbx_continent4_templates.xml** 

автозаполнение полей инвентаризации;  

триггеры ICMP-ответа (по умолчанию отключено);  
графики и триггеры загрузки процессора, памяти, swap-файла и дисков;  
графики и триггеры загрузки, разных событий и ошибок на сетевых интерфейсах;  
комплексный экран графиков всех сетевых интерфейсов;  
триггеры превышения температуры;  
триггер рассинхронизации времени;  
триггер смены имени узла;  
триггеры падения VPN;  

автоматическое определение наличия сервера доступа на криптошлюзе;  
для сервера доступа график количества подключений;  
для сервера доступа триггер недостаточности свободных лицензий.  

автоматическое определение наличия IPS на криптошлюзе;  
для IPS графики трафика и оповещений;  

автоматическое определение наличия МСЭ на криптошлюзе;  
для МСЭ график трафика;  

### шаблон Zabbix 5 EIGRP для устройств Cisco
**zbx_eigrp_template.xml**

обнаружение EIGRP-соседей;  
сбор данных по RTO и SRTT;  
триггеры потери соседства, большого SRTT и RTO;  
график SRTT;  
комплексный экран всех графиков SRTT;  
