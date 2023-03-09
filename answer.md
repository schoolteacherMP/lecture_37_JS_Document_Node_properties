## Задача 1.   
### Заменить текст  
![image](https://user-images.githubusercontent.com/113675674/215451969-78138185-92a2-4031-9db5-7ba10b152f4e.png)  

## Задача 2.   
### Добавить элемент  
![image](https://user-images.githubusercontent.com/113675674/215452898-2683ecde-e32f-442a-98db-d4188d59558d.png)  

## Задача 3.   
### Одинаковые параграфы 
`document.getElementById("text1").outerHTML = document.getElementById("text2").outerHTML;`  

## Задача 4.   
### Меняем текст по назатию  
![image](https://user-images.githubusercontent.com/113675674/215454270-7a27f0b1-7b07-465e-a3de-6b33c6224d37.png)  

## Задача 5.   
### Делаем невидимый параграф  
![image](https://user-images.githubusercontent.com/113675674/215454721-6e525d3d-fdf6-41f7-8370-14e0f40fc09f.png)  


## Задача 6.   
### меняем цвет  
![image](https://user-images.githubusercontent.com/113675674/224027659-ea387728-b3e6-4bb5-9055-5cee30b9953a.png)  
![image](https://user-images.githubusercontent.com/113675674/224027730-29133ddd-eaa6-4876-9e77-a2768fe005ff.png)  


## Задача 7.   
### Получите атрибут  
![image](https://user-images.githubusercontent.com/113675674/216936994-3dbc0453-460d-4c0d-a19f-8b9e563c544c.png)  


## Задача 8.   
### Сделайте внешние ссылки оранжевыми  
Во-первых, мы должны найти все внешние ссылки.  
Это можно сделать двумя способами.  
Первый – это найти все ссылки, используя document.querySelectorAll('a'), а затем отфильтровать ненужное:  
![image](https://user-images.githubusercontent.com/113675674/216937916-3036874e-39dd-45f4-ab7c-a966a3c7bc1e.png)  
Пожалуйста, обратите внимание: мы используем link.getAttribute('href'). Не link.href, потому что нам нужно значение из HTML.  
…Другой, более простой путь – добавить проверку в CSS-селектор:  
![image](https://user-images.githubusercontent.com/113675674/216937994-00d0919e-f5e9-4d68-b579-389a3d589a37.png)  





