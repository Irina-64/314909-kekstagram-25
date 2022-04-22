## 1. Загрузка нового изображения на сайт и заполнение информации о нём
### 1.1. Загрузка нового изображения:

выбор файла с изображением для загрузки;
изменение масштаба изображения;
применение одного из заранее заготовленных эффектов;
выбор глубины эффекта с помощью ползунка;
добавление текстового комментария;
добавление хэш-тегов.

### 1.2. Выбор изображения для загрузки осуществляется с помощью стандартного контрола загрузки файла #upload-file, 
который стилизован под букву «О» в логотипе. После выбора изображения (изменения значения поля #upload-file), 
показывается форма редактирования изображения. У элемента .img-upload__overlay удаляется класс hidden, 
а body задаётся класс modal-open.

После выбора изображения пользователем с помощью стандартного контрола загрузки файла #upload-file, 
нужно подставить его в форму редактирования вместо тестового изображения.

### 1.3 Закрытие формы редактирования изображения 

производится либо нажатием на кнопку #upload-cancel, либо нажатием клавиши Esc. 
Элементу .img-upload__overlay возвращается класс hidden. 
У элемента body удаляется класс modal-open.