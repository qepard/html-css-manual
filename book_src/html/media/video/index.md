# Добавление видеоконтента на страницу

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
## `<video>`

Элемент `<video>` обладает целым набором атрибутов, позволяющих управлять воспроизведением видеоролика.

## `src`
Данный атрибут позволяет указать расположение нужного видеофайла.

## `poster`
Данный атрибут позволяет установить изображение, показываемое в процессе загрузки видеоконтента и до момента, пока посетитель не начнет воспроизведение ролика.

## `width`, `height`
Эти атрибуты определяют размеры окна проигрывателя в пикселах.

## `controls`
Этот атрибут используется, если требуется, чтобы браузер предоставил собственные элементы управления воспроизведением.

## `autoplay`
Этот атрибут используется, если требуется, чтобы видеоролик автоматически начинал воспроизводиться после загрузки.

## `loop`
Этот атрибут используется, если требуется, чтобы проигрыватель автоматически повторял воспроизведение видеоролика.

## `auto`
Браузер должен загрузить видеоролик по окончании загрузки страницы

</div>
<div style="flex:1;width:60%;" markdown>

```html title="Код"
<!DOCTYPE html>
<html>
    <head>
        <title>
            HTML5: добавление видео на страницу
        </title>
    </head>
    <body>
        <video src="video/puppy.mp4"
        poster="images/puppy.jpg"
        width="400" height="300"
        preload
        controls
        loop>
        <p>Играющие щенки</p>
        </video>
    </body>
</html>
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/videoex.gif"></figure>

В языке **HTML5** не обязательно присваивать значения атрибутам `controls`, `autoplay` и `loop`, используемым с элементом `<video>`. Эти атрибуты подобны переключателям. Если атрибут указан, значит, данная функция считается включенной, если не указан - соответственно, отключенной.

## `preloaded`
Данный атрибут дает браузеру инструкцию, что следует сделать при загрузке страницы. Он может принимать одно из следующих трех значений.

## `none`
Браузер не должен начинать загрузку видеоролика, пока пользователь не щелкнет мышью по кнопке Воспроизведение.
Если браузер не поддерживает элемент `<video>` или формат используемого видеофайла, то на экран будет выведена информация, помещенная между открывающим `<video>` и закрывающим `</video>` тегами.

## `metadata`
Браузер должен лишь собрать такую метаинформацию, как размер видео, первый кадр, список воспроизведения и длительность.

</div></div>

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/media/images'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая глава</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/media/video/source'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
