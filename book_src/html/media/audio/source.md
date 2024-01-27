# Несколько источников аудиоконтента

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
## `<source>`
С помощью элемента `<source>`, помещаемо- го между открывающим `<audio>` и закрывающим `</audio>` тегами, можно указать несколько аудиофайлов, используемых проигрывателем (вместо использования атрибута `src` элемента `<audio>`).

## `src`
Атрибут `src` используется с элементом `<source>` для указания местоположения нужного файла.

</div>
<div style="flex:1;width:60%;" markdown>

```html title="Код"
<!DOCTYPE html>
<html>
    <head>
    <title>
        HTML5: несколько источников аудиоконтента
    </title>
    </head>
    <body>
        <audio controls autoplay>
        <source src="audio/test-audio.ogg"/>
        <source src="audio/test-audio.mp3"/>
        <p>Ваш браузер не поддерживает формат данного аудиофайла.</p>
        </audio>
    </body>
</html>
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/audioex.gif"></figure></div></div>

Элемент `<audio>` языка **HTML5** не получил столь широкого распространения, как элемент `<video>`, и, кроме того, в первых версиях браузеров, поддерживавших этот элемент, возникали проблемы с качеством воспроизведения аудиозаписей.

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/audio'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/tables'"><span style="margin: 0 10px;">Следующая глава</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
