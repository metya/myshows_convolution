# myshows_convolution
букмарклет для сворачивания всех сериалов на странице сериалов


Так как гитхаб не поддерживает букмарклет ссылки, то придется сделать ее самим, но это просто. 

Надо на панели закладок добавить новую закладку и назвать ее как нибудь как вам нравится. 
Потом нажать редактировать закладку и в поле адреса ввести код ниже, нажать сохранить, и все!

```js
javascript: (function(){$('div.seasonBlock').each(function() {closeSeasonBlock(this.id);}); saveCookies(); alert('Все свернуто! Перезагрузи страницу.');})();
```

После этого, на странице сериалов (на http://myshows.me/profile/) можно просто нажать на закладку и все сериалы свернутся.

