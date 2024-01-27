# Атрибут ID

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
Каждый **HTML**-элемент может иметь атрибут `id`.

Он используется для идентификации, поэтому его значение должно быть уникальным для каждого элемента на странице.

Значение атрибута может начинаться с латинской буквы или со знака подчеркивания (но не с цифры или другого символа).

Очень важно, чтобы значения атрибута `id` не повторялись на странице (в противном случае они не будут уникальными).

В примере справа абзац со значением `pullquote` атрибута `id` с помощью **CSS** выделен прописными буквами.

</div>
<div style="flex:1;width:60%;" markdown>

```html title="Код"
<p>
    Вода и воздух. 
    Как обыденны и банальны эти две субстанции: 
    они едва ли привлекают к себе чье-то внимание, 
    но, тем не менее, они обеспечивают наше существование.
</p>
<p id="pullquote">
    Каждый раз, смотря на море, во мне рождается успокаивающее чувство защищенности, 
    подобно тому, что появляется во время посещения родительского дома; 
    я словно отправляюсь в морское путешествие, а это путешествие есть наблюдение.</p>
<p>Самая тайная тайна: вода и воздух здесь, рядом с нами: в море.</p>
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/id.png"></figure></div></div>

Если вы продолжите обучение знакомством с языком **JavaScript** (позволяющим сделать созданную вами страницу интерактивной), то увидите, что атрибуты `id` используются, чтобы написанный сценарий работал с конкретными элементами разметки.

Атрибут `id` называют глобальным, поскольку он может быть использован с любыми **HTML**-элементами.

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/class'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
