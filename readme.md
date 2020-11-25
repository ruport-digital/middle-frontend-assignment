# Тестовое задание для Middle Frontend Developer

Сверстать страницу распределения заявок на сайте клуба медведей.

Отрисовка карточек происходит на стороне клиента.

Фильтр состоит из статуса нахождения в заповеднике и трех категорий заявок: текущие, отклоненные, принятые.

Когда пользователь отклоняет или принимает заявку, отправляется запрос с параметром id, при положительном ответе карточка перемещается в соответствующую категорию.

Требования:
- ECMAScript 6
- SCSS
- Не использовать фреймворки и библиотеки
- Адаптивность

Эндпоинты для:
- [Получения данных](https://private-9d5e37a-testassignment.apiary-mock.com/get-bears) - GET
- [Принять заявку](https://private-9d5e37a-testassignment.apiary-mock.com/resolve-bear) - POST
- [Отклонить заявку](https://private-9d5e37a-testassignment.apiary-mock.com/reject-bear) - POST


Макет страницы смотреть на [figma](https://www.figma.com/file/R5a8WGXugppqa8EtcYIbbF/TEST).
