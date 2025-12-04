# Roblox-zapret


В России начали появляться ошибки у игроков Roblox.

- Ошибка 17
  
Я нашел решение как исправить ошибку:
Для этого заходим в ваш запрет. 

Если его у вас нет то вот ссылка:
Zapret - [ТЫК](https://github.com/Flowseal/zapret-discord-youtube)

1. Открываем папку lists

2. Открываем файл list-general.txt

3. Вписываем адрес: roblox.com


Если у вас запущен запрет во время редактирования -- перезапустите

Все после выполнения этих действий у вас должен работать роблокс без этой ошибки


### КАК ЛЕГКО ОБОЙТИ БЛОКИРОВКУ РОБЛОКСА (гайд для самых маленьких)
Для начала у вас должен быть запрет последней версии (_1.9.0b на момент написания данного текста_), включите в service.bat 6 и 7 пункты, а именно **Switch Game Filter** из `disabled` в `enabled`, и **Switch ipset** на `any` 
_(необходимые параметры выделены на скриншоте)_
<img width="302" height="235" alt="Image" src="https://github.com/user-attachments/assets/556b500c-93af-476b-832d-0c3ac29d47d0" />
После этого добавьте в текстовый файл с доменами по пути `Папка запрета/lists/list-general.txt` следующие домены

```
roblox.com
www.roblox.com
rbxcdn.com
rbxinfra.net
rbxtrk.com
roblox.co.uk
roblox.us
roblox.de
roblox.fr
roblox.jp
roblox.tv
css.rbxcdn.com
js.rbxcdn.com
ecsv2.roblox.com
metrics.roblox.com
apis.roblox.com
realtime-signalr.roblox.com
games.roblox.com
tr.rbxcdn.com
thumbnails.roblox.com
```

!!! Если у вас был открыт запрет во время изменения в текстовом файле, перезапустите ег