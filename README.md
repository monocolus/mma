# My Conky Configuration
> Сделал свой вариант конфига для [коньков](https://github.com/brndnmtthws/conky), может кому полезно.

К конькам прикрутил следующие скрипты:

- Отоброжение балланска Qiwi кошелька. 
- Отображение информации о треке ил Spotify.

## Установка
1. Установите Conky и Python версии не ниже 3.6 через свой менеджер пакетов.
2. Клонируйте репозиторий при помощи git и перейдите в папку:
 ```bash
    git clone https://github.com/monocolus/myconkyconf
    cd myconkyconf
```
3. Вставте в файл qi.py ваш [Qiwi Api](https://qiwi.com/api), и номер телефона:
 ```bash
    wallet = pyqiwi.Wallet(token='fsffysigf', number='71321334576')
```
4. Запустите командой:
```bash
    conky -c conky.conf
```

## Скриншот:

[![screenshot](https://github.com/monocolus/myconkyconf/blob/main/screen.png?raw=true)]

