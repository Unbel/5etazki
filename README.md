# 5etazki
Исходный код сайта про снос пятиэтажек. Код для генератора статических сайтов hugo.

Это исходный код сайта про снос хрущёвок: http://5etazki.ru
Поскольку большая посещаемость и спешка не предполагается, то я решил сделать всё как-надо. 

# Технические детали

Сайт сделан статически генерируемым - потому что я не хочу тратить много денег на свои увлечения - я же не задрот.

Фотографии хостятся на flickr, и ссылки на них генерируются сторонним сервером http://photo2blog.ru на этапе написания текста.

Хоть это и снижает надёжность - flickr имеет право закрытся, но с другой стороны у меня нет ограничений на трафик, и повышается популярность моего аккаунта на фликре.

Сайт генерируется генератором hugo: http://gohugo.com. Он создаёт папку с html-файлами, которая вручную закачивается на ftp.
Исходный код выложен на github, потому что я использую разные компьютеры.

Сайт и этот репозиторий рассчитаны на использование только русского языка (мультиязычным будет следующий сайт) и OS Windows (потому что на Ubuntu аналоги моих любимых графических приложений жутко тормозят). 

# Как поднять 5etazki.ru у себя

Установить hugo

Клонировать репозиторий
```
hugo server
```

# Что конкретно ты можешь сделать в репозитории

* Заводить тикеты с пожеланиями
* Писать тексты про серии домов, и заливать их в тикеты или пулл-реквестами
