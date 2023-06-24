## Список завершенных бесплатных проектов

1. **Senex**
    - виджет рабочего стола, показывающий информацию о погоде и пробках на дорогах
        <details><summary>Скриншот</summary>
            <img src="https://github.com/0xMihalich/Senex/blob/main/Senex.jpg" width="500">
        </details>
        <details><summary>Описание</summary>
            <dl>
                <dt>Приложение работает как виджет, закрытие программы и другие настройки доступны при нажатии правой кнопкой на значек в трее.</dt>
                <dt>Ограничения:</dt>
                <dd>Только русские населенные пункты, теоретически другие страны будут работать, но город отображаться не будет.</dd>
                <dd>Яндекс выдает сводку о дорожной ситуации только в некоторых городах, если ваш город не в их числе, будет выводиться сообщение "нет информации".</dd>
                <dd>Сам openweather выдает только населенный пункт, в базу собрал все города, но прицепить ко всем регионы задача не совсем простая.</dd>
            </dl>
        </details>
    
        [Скачать готовую сборку для Windows 7-11 x32/x64](https://drive.google.com/file/d/1RIPkeBIyG_7yPNlL0slLLRwTdt-hnwDs)

        [Исходный код](https://github.com/0xMihalich/Senex)

2. **Savedgram**
    - автоматическое сохранение файлов и фото из Telegram в нужную папку на рабочем ПК через фоновое приложение
        <details><summary>Скриншоты</summary>
            <img src="https://github.com/0xMihalich/my_projects_for_all/blob/main/images/savedgram/main.png" width="500">
            <img src="https://github.com/0xMihalich/my_projects_for_all/blob/main/images/savedgram/tray1.png" width="500">
            <img src="https://github.com/0xMihalich/my_projects_for_all/blob/main/images/savedgram/tray2.png" width="500">
        </details>
        <details><summary>Описание</summary>
            <dl>
                <dt>Программа для быстрого сохранения фото, видео и файлов до 20 мб из Telegram в папку на ПК.</dt>
                <dd>для работы программы нужно создать бота через https://t.me/BotFather и ввести его токен в окно программы, выбрать папку на компе куда будет сохраняться все что вы кидаете боту и нажать на **Start**.</dd>
                <dd>Если папка и токен указаны верно, программа свернется в трей и будет в фоновом режиме автоматически сохранять файлы на ПК.</dd>
                <dd>Настройки программы в зашифрованном виде автоматически сохраняться в папке с программой.</dd>
                <dd>Сборка под Windows 10 64 бит. Для других систем можно использовать исходный код или собирать самостоятельно</dd>
                <dt>Изменения в актуальной версии кода:</dt>
                <dd>добавил поддержку Linux и Macos.</dd>
                <dd>добавил все типы медиа (голос, аудио, файлы, картинки, анимации, видео).</dd>
                <dd>добавил проверку, что файл не превышает 20мб.</dd>
            </dl>
        </details>
    
        [Скачать готовую сборку для Windows 10-11 x64](https://drive.google.com/file/d/1wM1NItkEjfd1CZiDQdb0kq6cyuet-Ml5)

        [Исходный код](https://github.com/0xMihalich/Savedgram)
3. **WEBMConvertor**
    - программа для конвертации любого видео в формат WEBM с выбором сжатия и возможностью отрезать звук для загрузки во внешние данные
        <details><summary>Скриншот</summary>
            <img src="https://github.com/0xMihalich/my_projects_for_all/blob/main/images/webmconv/screenshot.jpg" width="500">
        </details>
        <details><summary>Описание</summary>
            <dl>
                <dt>Конвертация любого видео в формат WEBM VP9</dt>
                <dt>Поддерживаемые форматы видео:</dt>
                <dd>.264 .3g2 .3gp .3gp2 .3gpp .amv .asf .avchd .avi .bdmv .bik .dav .divx .dv .evo .f4v .flv .gif .hdmov .ifo .ivf .m1v .m2p .m2t .m2ts .m2v .m4v .mk3d .mkv .mov .mp2v .mp4 .mp4v .mpe .mpeg .mpg .mpls .mpv .mpv2 .mpv4 .mts .mxf .ogm .ogv .png .qt .ram .rec .rm .rmvb .smk .ssif .swf .tp .trp .ts .video .vob .webm .wmv .wtv</dd>
                <dt>Доступные настройки:</dt>
                <dd>Изменить имя сохраняемого файла.</dd>
                <dd>Выбрать степень сжатия.</dd>
                <dd>Убрать звук из видео.</dd>
                <dt>Зависит от Ffmpeg, для исключения вопросов как его установить актуальная версия уже добавлена в программу</dt>
                <dt>Сборка для других систем мной делаться не будет, но по запросу дам исходники программы если кто-то хочет собрать под MacOS или Linux</dt>
            </dl>
        </details>
    
        [Скачать готовую сборку для Windows 7-11 x32/x64](https://drive.google.com/file/d/13iv7m-TMGOBJGmFR-JskkKHiQcYKJQok)

4. **AlterFAT**
    - программа для быстрого форматирования карт памяти и USB-флешек емкостью от 9 КБ до 2 ТБ в FAT12/FAT16/FAT32/exFAT. Доступно форматирование раздела более 32 ГБ в FAT32
        <details><summary>Скриншот</summary>
            <img src="https://github.com/0xMihalich/alterfat/blob/main/screen.jpg" width="500">
        </details>
        <details><summary>Описание</summary>
            <dl>
                <dt>Особенности программы:</dt>
                <dd>Размер кластера выбирается автоматически</dd>
                <dd>Поддерживается только быстрое форматирование раздела, для Low lewel форматирования рекомендуется использовать другие программы, если это необходимо</dd>
                <dd>Программа видит всю память устройства, что является хорошим решением для форматирования памяти, которую Windows отказался форматировать по причине наличия на ней множества разделов</dd>
                <dd>Тип загрузочной записи MBR</dd>
                <dt>Отличие от стандартных средств Windows:</dt>
                <dd>Нет лишней информации в MBR секторе (Головка, Сектор, Цилиндр), являющейся необходимой для HDD и абсолютно не нужной для устройств с NAND</dd>
                <dd>Код типа раздела в MBR явно указывает на структуру FAT для любых устройств, в отличие от Windows, указывающей том с поддержкой LBA (системы без поддержки LBA не пытаются открыть такой раздел)</dd>
                <dd>Файловая система создается сразу со второго сектора, что дает возможность использовать все доступное место</dd>
                <dd>Поддержка карт памяти и USB-флешек емкостью до 2 ТБ (2199023255552 байт)</dd>
                <dd>Метка тома поддерживает любой регистр букв</dd>
                <dd>Длина метки тома до 11 символов для FAT12/FAT16/FAT32 и до 15 символов для exFAT</dd>
                <dd>Раздел от 32.5 МБ (34089472 байт) до 2 ТБ (2199023255040 байт) разрешено форматировать в файловую систему FAT32 (карта памяти может быть использована в сотовых телефонах, регистраторах, телевизорах, nintendo 3ds/ds и других устройствах)</dd>
            </dl>
        </details>
    
        [Скачать готовую сборку для Windows 7-11 x32/x64](https://drive.google.com/file/d/1w4AGRBT4lYr3qg--Ia8ypPu-j2-Xu9bF)

        [Исходный код](https://github.com/0xMihalich/alterfat)

5. **UUID_Changer**
    - программа для быстрого выбора нужного UUID для записи IMEI, T-Key и Google Key в новую материнскую плату на устройствах Blackview и Oukitel
        <details><summary>Скриншот</summary>
            <img src="https://github.com/0xMihalich/my_projects_for_all/blob/main/images/uuid_changer/screen.jpg" width="500">
        </details>
        <details><summary>Описание</summary>
            <dl>
                <dt>Список доступных моделей на данный момент:</dt>
                <dd>Blackview: A60, A60Pro, A80, A80Pro, A100, BV4900, BV4900Pro, BV5500Pro, BV5500Plus, BV5900, BV6600, BV6600PRO, BV6900, BV8800, BV9100, BV9500Plus, BV9900E, TAB10</dd>
                <dd>Oukitel: C21Pro, WP5, WP5Pro, WP8Pro, WP9, WP12, WP12Pro, WP13, WP15, WP16</dd>
                <dd>Для добавления новой модели необходимо отредактировать файл models.ini</dd>
                <dd>Для обновления ip-адреса и названия сервера необходимо отредактировать файл settings.ini</dd>
                <dd>Для автоматического обновления файла C:\Windows\System32\drivers\etc\hosts программа должна быть запущена от имени администратора</dd>
                <dt>Как пользоваться:</dt>
                <dd>1. Запустить программу и указать путь до SN_Write_Tool, которой будем пользоваться</dd>
                <dd>2. Если путь к программе верный, станет активна кнопка Start SN Write Tool, если путь неверный, кнопка останется серой</dd>
                <dd>3. При верном указании директории программы путь к программе автоматически сохраниться в файле settings.ini</dd>
                <dd>4. Выбрать брэнд и нужную модель из списка</dd>
                <dd>5. Нажать на Start SN Write Tool</dd>
                <dd>6. Программа автоматически внесет изменения в файл [SN Write Tool]\tee_stuff\kph_in\kph_env.ini и запустит программу SN_Write_Tool</dd>
            </dl>
        </details>
    
        [Скачать готовую сборку для Windows 7-11 x64](https://drive.google.com/file/d/1sEqvT6wbYuaClYMum1OOLuqb2KX618Po)
        
        #### Пароль на архив 12345678
        
        **ВНИМАНИЕ!** В поиске UUID для Blackview A80S BV5100 BV5100Pro BV5500 BV6100 BV6300 BV6300Pro BV9700Pro BV9800 BV9800Pro BV9900 BV9900Pro и DEXP GS153
        
        Если у кого-то есть что-то из этого списка, свяжитесь со мной любым удобным способом

Связь со мной:

[Telegram](https://t.me/OxMihalich)

[Whatsapp](https://api.whatsapp.com/send?phone=79242525987)

[Skype](https://join.skype.com/invite/dncj29ggTB8o)

[Мой Github](https://github.com/0xMihalich)
