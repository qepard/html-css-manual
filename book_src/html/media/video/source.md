# Несколько источников видеоконтента

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
## `<source>`

Для указания расположения видеофайла вы можете воспользоваться элементом `<source>`, помещаемым внутрь элемента `<video>`. (Данный элемент призван заменить атрибут `src` тега `<video>`.)

Для обозначения того, что видеоролик доступен в нескольких форматах, вы можете использовать несколько элементов `<source>`.

## `src`
Данный атрибут служит для указания пути к видеофайлу.

## `type`
Используйте этот атрибут для указания формата видеофайла. В противном случае браузер загрузит часть видеофайла, чтобы проверить возможность воспроизведения, что займет некоторое время и повлечет лишний расход трафика.

## `codecs`
В атрибуте `type` необходимо указать кодек для конвертирования видео. Обратите внимание на использование двойных и одинарных кавычек при указании атрибута `type`.

</div>
<div style="flex:1;width:60%;" markdown>

```html title="Пример"
<!DOCTYPE html>
<html>
    <head>
        <title>
            HTML5: несколько источников видео
        </title>
    </head>
    <body>
        <video poster="images/puppy.jpg" width="400"
        height="320" preload controls loop>
        
        <source src="video/puppy.mp4"
        type='video/mp4;codecs="avc1.42E01E, mp4a.40.2"'/>
        
        <source src="video/puppy.webm" 
        type='video/webm; codecs="vp8, vorbis"'/>

        <p>Играющие щенки</p>
        </video>
    </body>
</html>
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/videoex.gif"></figure>

Если браузер не поддерживает элемент `<video>` или формат используемого видеофайла, то на экран будет выведена информация, помещенная между открывающим `<video>` и закрывающим </video> тегами.

## <span style="color:#E34C26;">ПРИМЕЧАНИЕ</span>

На <a href="https://htmlandcssbook.com/extras/encoding-videos-for-the-web/">этой странице</a> размещено несколько ссылок на инструменты, позволяющие конвертировать видео и аудиофайлы в требуемый формат.

</div></div>

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/media/video'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/media/audio'"><span style="margin: 0 10px;">Следующая глава</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
