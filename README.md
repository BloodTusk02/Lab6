Создадим проект. Добавим 2 кнопки, TextView и поле EditText.  
![изображение](https://user-images.githubusercontent.com/79984303/134776105-ea5fd1eb-5c60-4aba-a546-5038b0db863d.png)  
![изображение](https://user-images.githubusercontent.com/79984303/134776127-1f9baceb-f2ca-4581-9ee1-f5af6e43b212.png)
Добавим обработчики кнопок:  
![изображение](https://user-images.githubusercontent.com/79984303/134776165-9f447201-1d18-461a-a48c-1d76a02698c6.png)  
Добавим следующий код (В методе onSaveInstanseState сохраняем введённые данные. В методе onRestoreInstanceState - восстанавливаем их):
![изображение](https://user-images.githubusercontent.com/79984303/134776186-e079c30c-d09f-407d-be53-a07b69eec8a9.png)  
Проверим работоспособность. Так как при повороте Activity уничтожается и заново создаётся, проверим сохранение данных поворотом телефона.  
![5fl71Q_veJs](https://user-images.githubusercontent.com/34157509/146221094-96de39a2-a370-461f-8db6-43e86acbe748.jpg)



  

