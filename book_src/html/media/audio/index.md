# Добавление аудиоконтента на страницу

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
## `<audio>`
В языке HTML5 используется элемент `<audio>`, позволяющий добавлять аудиозаписи на веб-страницу. Точно так же, как и в случае с добавлением видео при помощи HTML5, разные браузеры поддерживают различные форматы аудиофайлов. Для элемента `<audio>` был создан ряд атрибутов, позволяющих управлять воспроизведением аудиозаписи.

## `src`
Данный атрибут определяет путь к нужному аудиофайлу.

## `controls`
Данный атрибут указывает, должен ли проигрыватель отображать элементы управления воспроизведением.

По умолчанию при его отсутствии элементы управления отображены не будут.

С помощью языка *JavaScript* вы также можете настроить отображение ваших собственных элементов управления.


</div>
<div style="flex:1;width:60%;" markdown>

```html title="Код"
<!DOCTYPE html>
<html>
    <head>
        <title>
            HTML5: добавление аудиоконтента на страницу
        </title>
    </head>
    <body>
        <audio src="audio/test-audio.ogg" controls autoplay>
        <p>Ваш браузер не поддерживает формат данного аудиофайла.</p>
        </audio>
    </body>
</html>
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/audioex.gif"></figure>

## `preload`
Данный атрибут указывает, какие действия должен выполнять браузер, если для проигрывателя не указан атрибут `autoplay`.

Данный атрибут может иметь те же самые значения, что и его аналог в элементе `<video>`.

## `loop`
Данный атрибут указывает, что по завершении воспроизведения аудиофайла оно должно автоматически начаться вновь.

</div></div>

## `autoplay`
Наличие этого атрибута указывает, что проигрывание аудиозаписи должно начинаться автоматически. (Однако рекомендуется позволить посетителям самостоятельно включать воспроизведение.)

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/media/video'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая глава</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/media/audio/source'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
