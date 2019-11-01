<h2>Список OSINT ресурсов</h2>

<a href="https://github.com/solkogan/osinto/blob/master/articles.md">Статьи по OSINT</a>
<a href="https://t.me/osinto">Мой Telegram канал по OSINT</a>

<b>Системы поиска людей:</b>

http://people.yandex.ru - поиск по ФИО, возрасту, городу, нику<br>
https://go.mail.ru/search_social? - поиск людей в соцсетях<br>
https://vk.com/search?c[section]=people - поиск людей ВК<br>
https://www.facebook.com/friends/requests/ - поиск в Фейсбуке<br>
https://twitter.com/search-advanced - поиск в Твиттер<br>
https://pipl.com/ - общемировая система поиска по соцсетям<br>
https://thatsthem.com - поиск по людям (зарубежье)<br> 

Иногда достаточно фамилии и города проживания. Найдется много людей пролистав фото которых, вы обнаружите искомого. Узнав из его аккаунта дату рождения, повторите поиск с этим же именем, но без фамилии или наоборот с этой же фамилией но без имени, или просто по точной дате рождения - так вы найдете левые акки человека с измененным ФИО или без ФИО, но с его фотками.

<b>Анализ соцсетей</b>

В соцсети ВК искать упоминания о человеке с помощью следующего URL-запроса: https://vk.com/feed?obj=ID&q=§ion=mentions где ID – это идентификатор пользователя ВК, который можно узнать, наведя курсор, например, на кнопку «Отправить сообщение»: цифры в ссылке и будут его ID. Также можно узнать ID ВК наведя курсор на фото аватарки человека.

http://searchlikes.ru - анализ лайков юзера ВК<br>
https://vk.com/age_teller - сервис который пытается определить возраст юзера по его социальным связям<br>
https://github.com/batuhaniskr/twitter-intelligence - для анализа твиттера<br>
https://github.com/twintproject/twint - анализ Твиттер<br>
https://github.com/sc1341/InstagramOSINT - анализ Инсты<br>

<b>Поиск по нику, логину</b>

Поиск где зарегистрирован данный ник, на популярных сайтах. При более-менее уникальном нике помогает находить дополнительные аккаунты искомого человека<br>
https://namechk.com<br>
https://knowem.com<br>
https://www.namecheckr.com<br>
http://usersherlock.com<br>
https://usersearch.org<br>

Если известен ник пользователя мы всегда можем просто набрать его логин в соответствующих профилю параметрах адресной строки данной соцсети. Например https://vk.com/supernick или https://my.mail.ru/mail/supernick

<b>Поиск по сотовому телефону</b>

http://t.me/get_kontakt_bot - бот в Telegram, ищет как подписан юзер у его друзей на мобилках<br>
https://play.google.com/store/apps/details?id=app.source.getcontact&hl=ru - приложение GetContact для Android<br>
https://play.google.com/store/apps/details?id=com.numbuster.android - еще одно приложение со схожим функционалом<br>
https://t.me/Smart_SearchBot - платный бот, получающий информацию о человеке и его ВК по номеру сотового (хорошо работает для давно зарегистрированных аккаунтов ВК)<br>
http://doska-org.ru - ищет номер сотового на досках объявлений<br>
https://smsc.ru/testhlr/ - доступен ли сотовый<br>
https://github.com/martinvigo/email2phonenumber - поиск сотового по емайлу<br>

Кроме этого можно добавить номер сотового в свои контакты на смартфон с установленными ВК, Viber, Whatsapp и импортировать в эти программы номер, чтобы увидеть сидит ли человек там, и извлечь с аккаунтов дополнительную информацию - например фото с Whatsapp.

Поищите номер в гугле, заключив его в двойные кавычки, с вариациями +7 и 8 в начале номера

<b>Поиск по фото</b>

https://play.google.com/store/apps/details?id=ru.profsoft.findclone - платная Android программа для поиска аккаунтов ВК по фото лица человека. Работает отлично.<br>
https://t.me/AvinfoBot - посылаешь боту фото с лицом, он в ответ присылает ссылку на профиль ВК. Работает нормально.<br>
https://findmevk.ru - бесплатный поиск по фото лица аккаунтов ВК - работает не очень<br>
https://github.com/solkogan/searchface - моя система поиска по лицам ВК для небольших городов<br>
https://azure.microsoft.com/en-us/services/cognitive-services/face/ - находится ли на двух разных фотках один и тот же человек<br>
https://github.com/ThoughtfulDev/EagleEye - система поиска лиц в соцсетях<br>
https://github.com/AivanF/ID-Detective-public - программа для поиска по биометрии ВКонтакте<br>

<b>Поиск по E-mail</b>

https://t.me/Smart_SearchBot - платный бот. Ищет аккаунт ВК и сотовый по e-mail. Хорошо работает с давно зарегистрированными аккаунтами

Поищите e-mail в гугле, заключив его в двойные кавычки

https://github.com/martinvigo/email2phonenumber - поиск сотового по емайлу<br>

<b>Пробив email на наличие в dump’ах старых паролей</b>

https://haveibeenpwned.com/ - показывает наличие емайла в слитых базах, и имя базы, но не сами пароли.<br>
https://leakcheck.net - платный сервис</br>
https://snusbase.com - еще один платный сервис<br>
https://monitor.firefox.com/breaches - информация о свежих утечках, позволяет искать базы по ключевым словам на форумах даркнета.<br>
https://github.com/woj-ciech/LeakLooker - поиск открытых баз через Shodan (нужен ключ)<br>
https://github.com/decoxviii/karma - поиск по утечкам<br>

<b>Работа с фотографиями</b>

Любая JPEG фотография, сделанная смартфоном с включенным GPS обычно содержит EXIF заголовки, которые позволяют определить место съемки. 

http://metapicz.com/#landing - определить EXIF заголовки фото<br>
https://owl.phy.queensu.ca/~phil/exiftool/ - программа для извлечения EXIF<br>
http://linkstore.ru/exif/<br>
http://exif.regex.info/exif.cgi<br>
http://imgops.com/<br>

https://images.google.com - поиск по картинкам Гугл<br>
https://www.google.com/advanced_image_search
https://images.yandex.ru - поиск по картинкам Яндекс<br>

Сочетайте обратный поиск фото с текстовыми запросами. Загрузите фотографию в Google Images. Если поисковик не выдает похожие фотографии, измените ключевое слово и по необходимости впишите в поле для поиска необходимую локацию. Например, если вы знаете, что фото было сделано в Швеции, впишите в поле для поиска возле фото «Site:se»

Вы можете заметить названия заведений, номера автомобилей, отражения в окне. Все это поможет вам идентифицировать место или время съемки. Чтоб установить размеры объектов на фото или расстояние между ними, найдите объект, размеры которого вам точно известны. Для определения расстояний можно использовать, например, столбы, которые размещаются на определенном расстоянии друг от друга.

<b>Вычисление домашнего адреса</b>

Узнать домашний адрес человека можно познакомившись с ним от имени противоположного пола и поинтересовавшись в каком районе города он живет. Далее по его фамилии и телефонной книге вычислить его точный адрес. Телефонные книги большинства населенных пунктов можно найти в сети интернет.

http://spra.vkaru.net/ - телефонная книга домашних телефонов СНГ с адресами проживания и фамилиями, не самая новая<br>
http://nomerorg.website/

Кроме того можно сделать специальный скрипт, который залогирует местонахождение человека или его точки доступа, при заходе этого человека на web-страничку со скриптом.

https://alexell.ru/network/mac-geo/ - Узнать местоположение по MAC-адресу Wi-Fi роутера

<b>Поиск по номеру или фото автомобиля</b>

https://avinfo.co/

<b>Поисковые системы</b>

https://cse.google.com/cse?cx=009462381166450434430:dqo-6rxvieq - гугл без капчи
https://github.com/j3ssie/Metabigor - использование поисковых систем без API ключей<br>
https://flightradar24.com - определение маршрутов самолетов в реальном времени<br>
http://www.advego.ru/plagiatus/ – программа для поиска плагиата (можно с помощью нее искать первоисточник текста или новости). <br>
http://go.mail.ru/realtime - как ни странно, ищет не хуже Яндекса<br>
https://www.mmnt.ru/int/ - поиск по FTP<br>
https://github.com/saeeddhqan/Maryam/wiki - мощный поисковый комбайн<br>

<b>Дампы и сливы</b>

https://darknetleaks.ru/archive/<br>
https://data.ddosecrets.com/file/<br>

<b>Методы социальной инженерии</b>

Узнав увлечения человека, группы, в которых он состоит ВК, исследователь может создать очень интересный для него сайт, где нужно регистрироваться (например, форум). Наполнив данный сайт интересной информацией с помощью копирования её с других ресурсов, и общаясь с объектом в интернете, ему могут подсказать ссылку на данный сайт. Есть большая вероятность, что человек при регистрации на данном сайте использует тот же самый пароль, что и для других используемых им сайтов. 

Соберите на человека досье, из найденной в сети информации, далее придумайте фейковую личность противоположного пола, и зарегистрировав фальшивый аккаунт, познакомьтесь с данным человеком в соцсетях. Обратим внимание на записи человека в соцсетях и сообщества в которые он вступил - они во многом отражают его внутреннее я. Зная увлечения человека, сойдитесь с ним в разговорах по его интересам, тогда он откроется, и возможно расскажет о себе больше, чем вы могли самостоятельно нагуглить. 

Стараемся стать сетевым другом/подругой для человека, помогаем ему советами, не забываем рассказывать о своей вымышленной личности, говорим про отношения, про детство, про работу, а также про какие-то вещи, от которых данный индивиддум фанатеет - программирование, выращивание кактусов, разведение бультерьеров, любимая рок-группа, любимый сериал.

Можно провести соцопрос, приодевшись и походив по квартирам его дома с официальной папочкой с бланками.. Если повезет, под видом соцопроса с красивой анкетой можно проникнуть в жилище объекта, получить ответы на некоторые вопросы, которые он сам заполнит в анкету. Помните, что подобным образом, случайные визитеры могут установить в вашем доме подслушивающие устройства или видеокамеры.

<b>Анализ сайта</b>

https://github.com/Nekmo/dirhunt -  программа для поиска директорий на сайте без брутфорса

<b>Архивация</b>

https://archive.is - просто введите URL-адрес страницы в красном поле, и Archive.is скопирует и сохранит его. <br>
http://osirtbrowser.com/ - удобный браузер со встроенной архивацией

<b>Разное</b>
https://t.me/@wifimapbot - покажет пароли Wi-fi недалеко от вас, если послать боту свою геометку
https://github.com/opsdisk/pagodo - Automate Google Hacking Database scraping 
