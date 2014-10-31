inflector
=========

Склонение числительных в русском языке

Если вам нужно просклонять существительное (или прилагательное) в завивисимости от употребленного с ним числительнго, например, `1 книга`, `2 книги`, `5 книг`, вы можете воспользоваться инфлектором.

``` javascript

var i = new Inflector(['книга', 'книги', 'книг']);
i.inflect(4); // "книги"
i.inflect(8); // "книг"

```
