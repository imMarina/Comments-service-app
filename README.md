# Comments-service-app
Itgirlschool project

## Practical task - description 

### week 12 homework
***** Задание под звездочкой 
Создадим сервис комментариев. В нём будет три поля ввода:

- поле для ввода имени. Сделайте интерфейс преобразования имени, который учтёт, все нюансы — лишние пробелы, отсутствие больших букв в имени и прочее. 
Например, было введено пользователем : `иВаН` .
Стало: `Иван` .
- поле для ввода ссылки на аватар;
- поле ввода сообщения. Необходимо реализовать отображение и добавление сообщений, а также функцию `checkSpam(str)`, заменяющую `'viagra'` или `'XXX'` на `***` ;
- функция должна быть нечувствительна к регистру:

### week 13 homework
  ***** Задание под звездочкой**
На прошлой неделе мы создали сервис комментариев. Давайте его улучшим:

- напротив аватара и имени должна появляться дата когда и во сколько был написан комментарий;
- под заголовком «Оставьте ваш комментарий» должен быть чекбокс, который даёт выбор показывать ваше имя в комментарии или нет;
- если пользователь не указал имя, то вместо имени должно появляться `username` ;
- если пользователь не ввел ссылку на аватар, то должна появляться стандартная аватарка. Стандартных аватаров должно быть больше пяти, они должны подставляться в рандомном порядке.
