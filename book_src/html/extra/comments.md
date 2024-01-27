# Комментарии в HTML

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
## `&lt;!-- --&gt;`

Если вы хотите включить в код какое-либо пояснение, которого не будет видно в браузерах посетителей, обозначьте нужный текст следующим образом:

`&lt;!-- текст комментария --&gt;`

Добавление комментариев рекомендуется, так как сколь хорошо бы вы ни знали код страницы на момент его написания, если вам придется вернуться к нему спустя какое-то время (или кому-либо еще понадобится просмотреть его), именно комментарии помогут разобраться, что есть что.

Кроме того, можно комментировать части кода для предотвращения их отображения.

</div>
<div style="flex:1;width:60%;" markdown>

``` html title="Код"
<!-- начало введения -->
<h1>Текущие выставки</h1>
<h2>Олафур Элиассон</h2>
<!-- конец введения -->
<!-- начало основного текста -->
<p>Олафур Элиассон родился в Копенгагене в семье переселенцев из Исландии.</p>
<p>Широкую известность он получил благодаря своим скульптурам и крупномасштабным инсталляциям 
    с использованием таких элементарных материалов, 
как свет, вода и температура воздуха для воздействия на зрительское восприятие.</p>
<!-- конец основного текста -->
<!-- <a href="mailto: info@primer.ru ">Связаться</a> -->
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/comments.png"></figure></div></div>

В этом примере вы увидите закомментированную гиперссылку.

Хотя комментарии не видны посетителям в основном окне браузера, любой желающий сможет увидеть их, просмотрев исходный код.

В объемных страницах вы часто встретите комментарии, поясняющие, где начинается или заканчивается тот или иной раздел, а также помогающие правильно интерпретировать код страницы.

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/types'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/id'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
