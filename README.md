# Проект Foodrgam
Проект Foodrgam это сайт, на котором пользователи могут публиковать рецепты, добавлять чужие рецепты в избранное и подписываться на публикации других авторов. Пользователям сайта также доступен сервис «Список покупок». Он позволяет создавать список продуктов, которые нужно купить для приготовления выбранных блюд.

# Проект Foodrgam состоит из страниц:

**Главная страница**
Содержит список первых шести рецептов, отсортированных по дате публикации «от новых к старым».

**Страница рецепта**
На странице находится полное описание рецепта. Авторизованные пользователи могут добавить рецепт в избранное и список покупок, а также подписаться на автора рецепта.

**Страница пользователя**
Содержит имя пользователя, все рецепты, опубликованные пользователем и возможность подписаться на пользователя.

**Страница подписок**
Содержит подписки пользователя. Подписаться на публикации могут только авторизованные пользователи.

**Избранное**
Содержит избранные рецепты пользователя. Содержит подписки пользователя. Список избранного может просмотреть только его владелец.

**Список покупок**
Содержит рецепты добавленные в список покупок. Пользователь нажимая кнопку «Скачать список» и получает файл с перечнем и количеством необходимых ингредиентов для всех рецептов, сохранённых в «Списке покупок».

# Ресурсы API YaMDb
**AUTH**: аутентификация.

**USERS**: пользователи.

**ТAGS**: тэги по которым может осуществляться фильтрация рецептов. Тэг может быть привязан к нескольким рецептам.

**RECIPES**: рецепты

**FAVORITE**: избранное 

**SHOPPING_CART**: список покупок.

**SUBSCRIBTION**: подписки пользователей

**INGREDIENTS**: ингридиенты. Ингридиент может быть привязан к нескольким рецептам.

# Пользовательские роли

**Неаутентифицированный пользователь** — может просматривать рецепты на главной, отдельные страницы рецептов и страницы пользователей.

**Аутентифицированный пользователь** — может читать всё, как и Неаутентифицированный пользователь, дополнительно может создавать, редактировать и удалять собственные рецепты; рааботать с персональным списком покупок: добавлять и удалять любые рецепты, выгружать файл с количеством необходимых ингредиентов для рецептов из списка покупок; работать с персональным списком избранного: добавлять в него рецепты или удалять их, просматривать свою страницу избранных рецептов; подписываться на публикации авторов рецептов и отменять подписки, просматривать свою страницу подписок

**Администратор** — полные права на управление проектом и всем его содержимым. Может создавать и удалять рецепты, тэги и ингридиент; измененять пароль любого пользователя; cоздавать, блокировать и удалять аккаунты пользователей;


Проект запущен и доступен по адресу [localhost:9000](http://localhost:9000/).

технологии проекта
-   [Python](https://www.python.org/)  - язык программирования.
-   [Django](https://www.djangoproject.com/)  - свободный фреймворк для веб-приложений на языке Python.
-   [Django REST Framework](https://www.django-rest-framework.org/)  - мощный и гибкий набор инструментов для создания веб-API.
-   [Djoser] - Библиотека djoser предоставляет набор представлений Django Rest Framework для выполнения основных действий, таких как регистрация, вход в систему, выход из системы, сброс пароля и активация учетной записи. Он работает с пользовательской моделью пользователя .
-   [React](https://react.dev/) - JavaScript-библиотека с открытым исходным кодом для разработки пользовательских интерфейсов.
-   [Node.js](https://nodejs.org/ru) - платформа с открытым исходным кодом для работы с языком JavaScript, построенная на движке Chrome V8
-   [Docker](https://www.docker.com/) - программное обеспечение для автоматизации развёртывания и управления приложениями в средах с поддержкой контейнеризации, контейнеризатор приложений.

