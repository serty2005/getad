Возможные значения "type_connect":

0 - режим автопоиска на виртуальных com-портах, работает также с 2-мя ФР, обязательный параметр: "com_baudrate".
1 - подключение по COM, обязательные параметры: "com_baudrate", "com_port".
2 - подключение по IP-адресу, обязательные параметры: "ip", "ip_port".
3 - usb-подключение, на самом деле при любом другом значении или полном отсутствии конфига утилита будет пытаться подключиться по usb.

Поддержка ДТО от 10.8.0.0 и выше. Если драйвер установлен старше, то можно подкинуть dll подходящей версии рядом с экзешником утилиты, тогда она будет использовать его.

После отработки скрипта, получаем json-файл со следующими полями:
{
    "modelName": "АТОЛ 22 v2 Ф",
    "serialNumber": "00123456790012",
    "RNM": "0000000001036518",
    "organizationName": "ООО Предприятие",
    "fn_serial": "7380440700067159",
    "datetime_reg": "2024-04-13 07:20:00",
    "dateTime_end": "2099-12-31 00:00:00",
    "ofdName": "ООО Эвотор ОФД",
    "bootVersion": "5.8.100",
    "ffdVersion": "105",
    "INN": "1111222233  ",
    "attribute_excise": "True",
    "attribute_marked": "False",
    "fnExecution": "Эмулятор ФН с поддержкой ФФД 1.2",
    "hostname": "Isaac-LT",
    "url_rms": "https://resto.iiko.it:443/resto",
    "teamviever_id": "111222333",
    "anydesk_id": "222333444",
    "total_space_sys": "476.83 Gb",
    "free_space_sys": "267.75 Gb"
}