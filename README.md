# SF-Console-Chat
Локальный консольный чат.

Исполнитель: Кирюшин Илья

* Консольная программа;
* Регистрация нескольких пользователей с использованием  логина, пароля и имени;
* Вход в чат по логину и паролю;
* Отправка текстового сообщения конкретному пользователю или всем пользователям чата;
* Просмотр сообщений текущего пользователя;

Добавлен класс User который содержит конструктор, геттеры и сеттеры для логина, пароля и имени;
Добавлен класс Message который содержит конструктор, геттеры и сеттеры для поля отправителя, получается сообщения, а также тела самого сообщения;
Добавлен класс Chat, содержащий контейнер пользователей чата, контейнер сообщений каждого пользователя, а также указатель на текущего пользователя;


Реализованы функции управления чатом:
* Меню чата chatOptions() предоставляет возможность выбрать регистрацию или войти в чат под уже существующим пользователем.
* Реализованы проверки на корректность воода данных; зарегистрировать пользователя  по уникальному логину, произвольному паролю и уникальному имени. 
* Реализваны проверки на уже существующего пользователя, на корректность ввода данных, а также опция exit выхода из чата; "залогинить" пользователя logIn().
* Реализованы проверки на корректность воода данных, на существование пользователя, а также опция logout, которая разлогинивает текущего пользователя и передает управление в меню чата; меню для текущего пользователя userOption() предоставляет возможность текущему пользователю написать сообщение, посмотреть список сообщений, либо разлогиниться, передав управление в меню чата; написать сообщение writeMessage() конкретному пользователю либо всем пользователям чата, включая текущего пользователя; показать сообщения текущего пользователя showMessages();
