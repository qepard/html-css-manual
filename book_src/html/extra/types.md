# Типы документов

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
Из-за существования нескольких версий языка **HTML** каждая веб-страница должна начинаться с объявления используемой версии языка при помощи элемента `DOCTYPE`.<br>(Впрочем, большинство браузеров отобразит страницу и без этого элемента.)

Использование объявления `DOCTYPE` способствует правильной обработке кода страницы браузером.

Перед объявлением не должно быть ничего, даже пробела.
</div>
<div style="flex:1;width:60%;" markdown>
Вот как выглядит объявление `DOCTYPE` для разных версий **HTML**:

``` html title="HTML5"
<!DOCTYPE html>
```

``` html title="HTML4"
<!DOCTYPE html PUBLIC
    "-//W3C//DTD HTML 4.01 Transitional//EN"
    "http://www.w3c.org/TR/html4/loose.dtd">
```

``` html title="Переходный XHTML 1.0"
<!DOCTYPE html PUBLIC
    "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3c.org/TR/xhtmll/DTD/xhtmll-transitional.dtd">
```

``` html title="Строгий XHMTL 1.0"
<!DOCTYPE html PUBLIC
    "-//W3C//DTD XHTML 1.0 Strict//EN"
    " http://www.w3c.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
```

``` html title="Объявление XML"
<?xml version="1.0" ?>
```
</div></div>

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/comments'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
