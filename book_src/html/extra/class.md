# Атрибут CLASS

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:40%;" markdown>
В языке **HTML** элементу также может быть присвоен атрибут `class`.

Иногда вместо идентификации каждого элемента разметки на странице гораздо удобнее оказывается выделить группу элементов.

Например введенный вами текст может содержать несколько абзацев, более важных, чем другие, или вы вдруг захотите выделить особым стилем ссылки, ведущие на страницы других сайтов и тем самым дать возможность посетителям отличать их от внутренних ссылок.

Чтобы сделать это, следует воспользоваться атрибутом `class`.

Его значение должно описывать, к какому классу принадлежит элемент.

В примере справа ключевым абзацам текста был присвоен атрибут `class` co значением `vazhno`.


</div>
<div style="flex:1;width:60%;" markdown>

```html title="Код"
<p class="vazhno">
    В течение года начиная с 15 января в Музее современного искусства 
    будет проводиться цикл из четырех выставок Хироши Сугимото.
</p>
<p>
    Каждая из четырех выставок будет представлять одну из четырех тем в работах художника: 
    "Наука", "Архитектура", "История" и "Религия". 
    Таким образом посетители смогут увидеть полную панораму творчества Хироши Сугимото.</p>    
<p class="vazhno chasy_raboty">
    Часы работы: 10:00-18:00 
    (после 17:30 посетители в музей не допускаются) .</p>
```

<figure><figcaption>Результат</figcaption><img src="/html-css-manual/assets/images/class.png"></figure>

<div style="display:flex;margin-top:-20px;" markdown>
<div style="flex:1;margin-right:20px;width:50%;" markdown>
По умолчанию использование этого атрибута не влияет на внешний вид элемента.

Он будет изменен только в том случае, если вы создадите специальное правило **CSS**.
</div>
<div style="flex:1;width:50%;" markdown>
В данном примере мы использовали средства **CSS**, чтобы отобразить элементы класса vazhno прописными буквами, а элементы со значением атрибута `class="chasy raboty"` красным цветом.
</div></div></div></div>

Нескольким элементам на странице допустимо иметь одно и то же значение элемента `class`.

Поэтому в данном примере значение vazhno может быть использовано и для заголовков, и для ссылок.

Если вы желаете указать, что какой-либо элемент относится к нескольким классам, то вы можете перечислить имена классов через пробел, как мы сделали это с третьим абзацем в примере.

<div style="display: flex; justify-content: space-between; padding: 20px; margin-top:30px;"><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/id'"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M15 18l-6-6 6-6" /></svg><span style="margin: 0 10px;">Предыдущая страница</span></button><button class="custom-button" style="background-color: rgb(0, 148, 133); color: white; font-family: 'Roboto', sans-serif; border: none; cursor: pointer; padding: 10px 20px; font-size: 16px; display: flex; align-items: center;" onclick="window.location.href='/html-css-manual/html/extra/div'"><span style="margin: 0 10px;">Следующая страница</span><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" style="fill: white; width: 20px; height: 20px;"><path d="M9 18l6-6-6-6" /></svg></button></div>
