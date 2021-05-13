[RU] 

Как установить мод на мой сервер?
- Подпишитесь на SQUAD MSF-C в Steam Workshop DayZ.
- Запустите DayZ, откроется DayZ Launcher и перейдите на вкладку Моды слева. В нижней части ваших модов поставьте галочку слева от мода SQUAD MSF-C. Это должно загрузить мод.
- Перейдите в программу Steam\steamapps\common\DayZ\!Workshop, и скопируйте папку @SQUAD MSF-C на свой рабочий стол или в нужное место.
- Поместите папку @SQUAD MSF-C в корневую папку вашего сервера DayZ.
- Скопируйте MSFC.bikey в папку ключей вашего сервера.
- В Параметрах запуска вашего Сервера добавьте "-mod=@SQUAD MSF-C".

Если у вас есть несколько модов, убедитесь, что внутренняя часть вашего текстового поля выглядит следующим образом.
Пример: @SQUAD MSF-C;@TestMod1;@ExperementalMod2;@OpenTest0;

Как установить Types.xml на мой сервер?
- По пути DayZServer\mpmissions\dayzOffline.chernarusplus\db
- Откройте файл types.xml
- Скопируйте те, которые вам нужные Types.xml из папки мода
- Вставьте его в самый конец строчного файла (DayZServer\mpmissions\dayzOffline.chernarusplus\db) types.xml
- По пути SpawnableTypes.xml откройте файл
- Вставьте его в самый конец строки файла (DayZServer\mpmissions\dayzOffline.chernarusplus) cfgspawnabletypes.xml

Как установить в TraderConfig?
- Откройте путь DayZServer\ServerProfile\Trader
- Откройте файл TraderConfig.txt
- Скопируйте те, которые вам нужные TraderConfigs из папки mod
- Вставьте его в самый конец строки файла (DayZServer\ServerProfile\Trader) TraderConfig.txt

Types.xml а TraderConfig меняйте на свое усмотрение, мы не запрещаем.

[EN] 

How to install mod to my server?
- Subscribe to SQUAD MSF-C in Steam Workshop DayZ.
- Start DayZ, initiate the DayZ Launcher, and click the Mods tab on your left. On the bottom of your Mods tick the box to the left of the SQUAD MSF-C mod. This should download the mod.
- Go to Program Steam\steamapps\common\DayZ\!Workshop, and copy the @SQUAD MSF-C folder to your desktop or desired location.
- Put the @SQUAD MSF-C folder into the root folder of your DayZ Server.
- Copy the MSFC.bikey into your keys folder of your server.
- In your Server Startup Parameters add "-mod=@SQUAD MSF-C".

If you have multiple mods, make sure the inside of your text field looks like this.
Example: @SQUAD MSF-C;@TestMod1;@ExperementalMod2;@OpenTest0;

How to install Types.xml to my server?
- Open DayZServer\mpmissions\dayzOffline.chernarusplus\db
- Open file types.xml
- Copy the ones you need Types.xml from the mod folder
- Paste it at the very end of the line file (DayZServer\mpmissions\dayzOffline.chernarusplus\db) types.xml 
- As well SpawnableTypes.xml open the file
- Paste it at the very end of the line file (DayZServer\mpmissions\dayzOffline.chernarusplus) cfgspawnabletypes.xml

How to install to my TraderConfig?
- Open DayZServer\ServerProfile\Trader
- Open file TraderConfig.txt
- Copy the ones you need TraderConfigs from the mod folder
- Paste it at the very end of the line file (DayZServer\ServerProfile\Trader) TraderConfig.txt

Types.xml and TraderConfig change at your discretion, we do not prohibit.