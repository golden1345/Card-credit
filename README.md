# Card-credit
Test_Best2Pay

Нужно сверстать форму по макету https://www.figma.com/file/SgHyJ9WM7sfjNTmqqITZel/Test_Best2Pay_?node-id=0%3A1
Форма адаптивная. Адаптив делается любым способом на ваше усмотрение, запрещено использовать bootstrap.

Для полей нужно настроить валидацию. Для реализации Вы используете библиотеки:
scripts/jquery-1.11.3.min.js
scripts/jquery.validate.js
Иные библиотеки запрещены, если потребуется доп. функционал - используйте jquery.

Структура проекта должна быть аккуратной, все файлы разнесены по семантическим разделам.

Для всех полей настроить правила валидации и придумать для них соответствующие сообщения об ошибках:
1. Для всех полей разрешено вводить только числа.
2. Для поля номер карты - ввод от 16 до 19 цифр, обязательное к заполнению поле. Ввод цифр разбить по 4 символа, то есть 1234 5678 1234 5678xxx. По желанию, реализовать проверку введенной карты по алгоритму Луна (https://ru.wikipedia.org/wiki/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC_%D0%9B%D1%83%D0%BD%D0%B0): если проверка провалена, выводится сообщение "Некорректный номер карты).
3. Для поля даты - обязательное поле. Пользователь вводит только цифры, "/" подставляется автоматически.
4. Для поля свс - ввод 3 цифр, обязательное поле.
Подсказка для свс появляется при наведении.
Кнопка отправить при открытии формы неактивна, актвизируется когда заполнены все поля корректно.
Перед отправкой формы всплывает confirm с заполненными данными. В случае готовности отправки формы (все валидации не провалены) - кнопка отправки блокируется для предотвращения повторного нажатия.
