# Сведения о странице

## `<meta>`
Элемент `<meta>` помещается внутрь элемента `<head>` и содержит информацию о текущей странице.

Его содержимое не видно посетителям, однако он выполняет множество функций, например сообщает поисковым системам информацию о странице, о том, кто ее создал, а также установлен ли для нее срок действия (если срок действия установлен, то страница может быть помечена как неактуальная).

Элемент `<meta>` пустой, поэтому ему не требуется закрывающий тег.

Для передачи информации в `<meta>` используются атрибуты.

Наиболее часто используемые атрибуты - это `name` и `content`, которые обычно используются вместе. Они устанавливают свойства всей страницы.

Значение атрибута `name` — это имя свойства страницы, которое вы хотите настроить, а значение атрибута `content` - новое значение, которое вы собираетесь присвоить данному свойству.

В первой строке исходного кода вы можете видеть элемент `<meta>`, в котором атрибут `name` используется для изменения описания страницы, а атрибут `content` это то место, где указывается ее новое описание.

Атрибуту name можно присвоить любое значение. Ниже перечислены несколько наиболее употребительных.

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:50%;" markdown>
## `description`

Значение этого атрибута является описанием страницы, оно чаще всего используется поисковыми системами для определения, чему та посвящена.

Длина описания не должна превышать **155 символов**.

Иногда описание может быть отображено в выдаче поисковой системы.

## `keywords`
Этот параметр должен содержать список ключевых слов, разделенных запятой, которые посетитель может использовать для поиска нужной информации.

На практике это свойство уже давно не влияет на индексацию страницы поисковой системой.

</div>
<div style="flex:1;width:50%;" markdown>
## `author`
Используется для указания имени автора веб-страницы.

## `pragma`
Данный параметр предотвращает кэширование страницы браузером. (Кэширование - это сохранение страницы на жестком диске компьютера посетителя для более быстрого ее открытия при повторном посещении.)
## `expires`
Так как браузеры зачастую кэшируют содержимое страниц, параметр `expires` может быть использован для указания того, когда устраницы должен истечь срок актуальности (и она должна быть удалена из кэша).

Обратите внимание, что дату нужно указывать строго в формате, который вы можете видеть в исходном коде примера.
</div></div>

## `robots`
Это свойство показывает, должны ли поисковые системы включать данную страницу в результаты поиска.

Значение `noindex` может быть использовано для запрета добавления страницы в результаты.

Значение `nofollow` устанавливает, что поисковые системы могут включать данную страницу в результаты поиска, но не должны показывать страницы, на которые ведут ссылки с нее.

```html title="Код"
<!DOCTYPE html>
<html>
    <head>
        <title>Сведения о ваших веб-страницах</title>
        <meta name="description" content="Эсce обискусстве инсталляций" />
        <meta name="keywords" content="инсталляция, искусство, мнение" />
        <meta name="robots" content="nofollow" />
        <meta http-equiv="author" content="Джон Даккет" />
        <meta http-equiv="pragma" content="no-cache" />
        <meta http-equiv="expires" content="Fri,05 Apr 2024 23:59:59 GMT" />
    </head>
    <body>
    </body>
</html>
```

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/span'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/example'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>