# OpenCart-Alphabank
Плагин <a href="https://pay.alfabank.ru/ecommerce/" target="_blank">платежного шлюза "Альфа-Банка"</a> для CMS OpenCart.
Используется для интеграции с Альфа-Банком и приемом платежей при помощи банковской карты. Подробнее узнавайте у специалистов "Альфа-Банка".

Разрабатывался на версии OpenCart CMS (v.2.0.3.1)

У меня основной модуль не заработал. Представляю форк кода, который у меня работает на Opecnart 2.0.3.1

----------------------------------------
### Подключение API от Альфа-Банка
#### Настройки OpenCart CMS

1. Загрузите модуль платежного шлюза "Альфа-Банка" с <a href="https://github.com/InterWaveRussia/OpenCart-Alphabank/">GitHub</a>
2. Загрузите файлы в папку с OpenCart CMS.
3. Войдите в панель управленияSign in to your OpenCart admin.
4. Кликните на **Модули** и выберите **Оплата**.
5. В строке **Альфабанк** в поле **Действие** выберите иконку карандаша (**Редактировать**).
6. Укажите ваш **Логин API** полученный от Альфа-Банка. (Различен для тестового и полного режима)
7. Укажите ваш **Пароль API** полученный от Альфа-Банка. (Различен для тестового и полного режима)
8. Выберите **Нет** в поле **Тестовый режим?** если вы хотите отключить режим тестирования и включить все возможности для приема платежей. (Не забудьте изменить **Логин** и **Пароль API** для НЕ тестового режима)
10. Выберите нужный вам **Статус заказа**, который будет установлен после проведения платежа для клиента.
11. Выберите **Включен** в поле **Статус** для подключения способа оплаты при оформлении заказа.
12. Сохраните ваши изменения.

#### Официальная поддержка плагина сотрудниками альфа-банка не предоставляется
----------------------------------------
# Лицензия
Данный модуль разработан <a href="http://iwaps.ru/" target="_blank">студией InterWave</a> и распространяется по лицензии OpenSource (MIT)


