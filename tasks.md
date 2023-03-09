## Задача 1.   
### Заменить текст  
Когда пользователь нажимает кнопку, используйте innerHTML для изменения текста в параграфе на "этот тест был изменен".  
Вставить код в HTML:  
`<p id="text">Исходный текст</p>  `  
`<button id="btn">Изменить текст</button>`  
Вставить код в JS:   
`document.getElementById("btn").addEventListener("click", function(){  
  //ваш код  
});`  

## Задача 2.   
### Добавить элемент  
Создайте HTML-документ с списком и кнопкой. Когда пользователь нажимает кнопку, используйте innerHTML для добавления нового элемента списка.  
Вставить код в HTML:  
`<ul id="list">`  
  `<li>Элемент 1</li>`  
  `<li>Элемент 2</li>`  
`</ul>`  
`<button id="btn">Добавить элемент</button>`     
Вставить код в JS:   
`document.getElementById("btn").addEventListener("click", function(){  
    //ваш код   
});
`

## Задача 3.   
### Одинаковые параграфы  
Создайте HTML-документ с двумя параграфами. Используйте outerHTML для замены текста в первом параграфе на текст из второго параграфа.  
Вставить код в HTML:  
`<p id="text1">Первый параграф</p>`  
`<p id="text2">Второй параграф</p>`  

## Задача 4.   
### Меняем текст по назатию  
Создайте HTML-документ с параграфом и кнопкой. Когда пользователь нажимает кнопку, используйте textContent для изменения текста в параграфе.  
Вставить код в HTML:  
`<p id="text">Исходный текст</p>`  
`<button id="btn">Изменить текст</button>`  
Вставить код в JS:  
`document.getElementById("btn").addEventListener("click", function(){  
 //ваш код     
});`  

## Задача 5.   
### Делаем невидимый параграф  
Создайте HTML-документ с кнопкой и параграфом. Когда пользователь нажимает кнопку, используйте hidden чтобы скрыть/показать параграф.  
Вставить код в HTML:  
`<p id="text">Текст</p>`  
`<button id="btn">Скрыть/показать</button>`  
Вставить код в JS: 
`document.getElementById("btn").addEventListener("click", function(){  
   //ваш код     
});`  



## Задача 6.   
### меняем цвет  
Есть div с текстом красного цвета и кнопка. При нажатии на кнопку цвет шрифта должен меняться с красного, на зеленый. Напишите CSS и реализуйте функционал.  
 `<div id="colorDiv" data-some-color="red">`  
      `Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam et`  
      `odio, repellat voluptate est veritatis adipisci eum repellendus eligendi`  
      `quidem ipsam saepe molestiae minus autem quaerat! Natus voluptas incidunt`  
      `aliquam.`  
    `</div>`  
    `<button id="btn">Изменить цвет</button>`  
    Вставить код в JS:  
`document.getElementById("btn").addEventListener("click", function(){  
 //ваш код     
});`  

## Задача 7.   
### Получите атрибут  
Напишите код для выбора элемента с атрибутом data-widget-name из документа и прочитайте его значение.  

  `<div data-widget-name="menu">Choose the genre</div>`  
  

## Задача 8.   
### Сделайте внешние ссылки оранжевыми  
Сделайте все внешние ссылки оранжевыми, изменяя их свойство style.  

Ссылка является внешней, если:  

Её href содержит ://  
Но не начинается с http://internal.com.  

`<a name="list">the list</a>`  
`<ul>`  
  `<li><a href="http://google.com">http://google.com</a></li>`  
 ` <li><a href="/tutorial">/tutorial.html</a></li>`  
  `<li><a href="local/path">local/path</a></li>`  
  `<li><a href="ftp://ftp.com/my.zip">ftp://ftp.com/my.zip</a></li>`  
  `<li><a href="http://nodejs.org">http://nodejs.org</a></li>`  
  `<li><a href="http://internal.com/test">http://internal.com/test</a></li>`  
`</ul>`  

`<script>`  
  // добавление стиля для одной ссылки  
  let link = document.querySelector('a');  
  link.style.color = 'orange';  
`</script>`  

![image](https://user-images.githubusercontent.com/113675674/216937645-77fba11a-e427-4715-9e7b-f276f7d9456c.png)  


