# opacity-to-scroll

<p>Изменение прозрачности при прокрутке страницы</p>

```js
  $(function(){
    $(window).scroll(function(){
      $('.header-main').css('opacity', 1 - $(window).scrollTop() / 800);
    });
  });
```
