### github pages

https://vodish.github.io/ace-emmet/

### ext-emmet.js

символ срабатывания

```
expand_abbreviation: { mac: "%", win: "%" },
```

### ace.js

сочитания

```
aa: '<a href="" target="_blank">',
```

### добавить в массив ace_line id строки
ace_line
16275
$renderLinesFragment
this.$lines


this.cells — массив объектов ячеек (cell), каждый элемент имеет следующие свойства:
    
    element: DOM-элемент div, которому присваивается класс ace_line (или ace_line_group).
    
    text: строка, содержащая текстовое содержимое строки (изначально пустая, заполняется при рендеринге).
    
    row: номер строки в документе (индекс).

Объекты создаются методом createCell (строка 15286-15294) и добавляются в массив через push/unshift. Массив используется для управления видимыми строками в слое текста редактора Ace.

