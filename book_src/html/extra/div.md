# Группировка текста и элементов в блок

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
## `&lt;div&gt;`

Элемент `<div>` позволяет сгруппировать несколько элементов в единый блок.

Например, вы можете создать `<div>`, объединяющий в себе все элементы заголовка сайта (логотип и панель навигации).

Вы также можете создать `<div>` для объединения комментариев посетителей сайта.

В браузере содержимое элемента `<div>` будет отображено с новой строки, никаких других изменений внешнего вида не произойдет.

Однако с помощью атрибутов `id` и `class` вы можете создать правило **CSS**, определяющее, сколько места будет занимать элемент `<div>` на экране, а также изменить внешний вид всех элементов, содержащихся в нем.

Кроме того, разобраться в вашем коде будет гораздо проще, если каждый раздел страницы вы заключите в отдельный элемент `<div>`.

</div>
<div style="flex:1;width:60%;" markdown>

```html title="Код"
<div id="header">
    <img src="images/logo.gif" 
    alt="Electric Universe" />
    <ul>
        <li>
            <a href="index.html">Главная</a>
        </li>
        <li>
            <a href="biography.html">Биография</a>
        </li>
        <li>
            <a href="works.html">Дискография</a>
        </li>
        <li>
            <a href="contact.html">Контакты</a>
        </li>
    </ul>
</div> <!-- конец заголовка -->
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/div.png"></figure>

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:50%;" markdown>
Так как внутри `<div>` может находиться несколько других элементов, комментарии после закрывающего тега `&lt;div&gt;` бывают очень полезны.
</div>
<div style="flex:1;width:50%;" markdown>
Это позволит вам четко видеть, к чему относится открывающий тег, как показано в последней строке примера.
</div>
</div>

</div></div>

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/class'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/span'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
