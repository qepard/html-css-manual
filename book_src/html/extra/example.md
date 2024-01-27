# Пример

Код примера начинается собъявления `DOCTYPE` для указания, что страница была написана на языке **HTML5**.

В `<head>` вы также можете видеть элементы `<meta>`, описывающие содержание страницы.

Для некоторых элементов установлены атрибуты `id` и `class`, указывающие их назначение.

Знак защиты авторских прав вставлен в текст с помощью соответствующего символа-мнемоника.

Отдельные части страницы сгруппированы с помощью элементов `<div>`, кроме того, к закрывающим тегам `</div>` добавлены комментарии, объясняющие, какую именно часть страницы они завершают.

```html title="Код"
<!DOCTYPE html>
<html>
    <head>
        <meta name="description" 
        content="Телефон и aдpеc Третьяковской галереи, Москва, Россия" />
        <title>Третьяковская галерея, Москва, Россия</title>
    </head>
    <body>
        <div id="header">
            <h1>Третьяковская галерея</h1>
            <ul>
                <li><a href="index.html">Главная</a></li>
                <li><a href="index.html">Галерея</a></li>
                <li class="current-page">
                    <a href="index.html">Адрес</a>
                </li>
            </ul>
        </div><!-- основная часть -->
        <div id="content">
            <p>г. Москва, Лаврушинский переулок, 10</p>
            <p>
                <span class="contact">Телефон:</span> 
                8(499)230-7788, (499)238-1378, (495)951-1362 </p>
            <img src="images/gallery.jpg" alt="Картина"/>
        </div>
        <!-- конец основной части -->
        <p>&coру; Третьяковская галерея</p>
    </body>
</html>
```

<center>[Результат](/html-css-manual/assets/files/EXTRAEX.html){ .md-button }

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/meta'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button></div>
