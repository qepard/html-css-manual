# Группировка текста и элементов в строку

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
## `&lt;span&gt;`

Элемент `<span>`- встроенный эквивалент элемента `<div>`.

Он используется для:

* окружения части текста, когда никакой другой элемент для этого не подходит
* окружения нескольких встроенных элементов.

</div>
<div style="flex:1;width:60%;" markdown>

```html title="Код"
<p>Electric Universe - проект в жанре
    <span class="psy">психоделический транс</span>, 
основанный в Германии в 1991 году.</p>
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/span.png"></figure></div></div>

Наиболее важная причина использования `<span>` - это возможность управлять внешним видом его содержимого с помощью средств **CSS**.

Довольно часто можно встретить использование атрибутов `id` и `class` с элементом `<span>`:

* для объяснения назначения элемента `<span>`
* для последующего применения стилей **CSS** к элементам.

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/div'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/meta'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
