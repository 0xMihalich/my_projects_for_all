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
    
        [Скачать готовую сборку для Windows 10 x64](https://drive.google.com/file/d/1wM1NItkEjfd1CZiDQdb0kq6cyuet-Ml5)

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
                <dt>Приложение работает как виджет, закрытие программы и другие настройки доступны при нажатии правой кнопкой на значек в трее.</dt>
                <dt>Ограничения:</dt>
                <dd>Только русские населенные пункты, теоретически другие страны будут работать, но город отображаться не будет.</dd>
                <dd>Яндекс выдает сводку о дорожной ситуации только в некоторых городах, если ваш город не в их числе, будет выводиться сообщение "нет информации".</dd>
                <dd>Сам openweather выдает только населенный пункт, в базу собрал все города, но прицепить ко всем регионы задача не совсем простая.</dd>
            </dl>
        </details>
    
        [Скачать готовую сборку для Windows 7-11 x32/x64](https://drive.google.com/file/d/1RIPkeBIyG_7yPNlL0slLLRwTdt-hnwDs)

        [Исходный код](https://github.com/0xMihalich/Senex)

5. **UUID_Changer**
    - программа для автоматического выбора нужного UUID для записи IMEI в новую материнскую плату на устройствах Blackview и Oukitel
