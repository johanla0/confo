## Участие в мероприятиях

### Регистрация в системе - SignUp
*Sea level*

Главный успешный сценарий:
1. Пользователь заполняет форму регистрации:
  - **email**
  - **ФИО**
  - страна
  - город
  - место работы, учёбы
  - должность, учёная степень
  - номер телефона
2. Пользователь получает на email подтверждение регистрации и данные для входа в личный кабинет

### Восстановление пароля - RestorePassword
*Sea level*

Главный успешный сценарий:
1. Пользователь выбирает опцию "восстановление пароля"
2. Пользователь получает на email ссылку для сброса пароля
3. Пользователь открывает ссылку, переходит на страницу установки нового пароля
4. Пользователь вводит и подтверждает новый пароль

### Регистрация на мероприятие - Participate
*Sea level*

Главный успешный сценарий:
1. Пользователь заполняет форму заявки:
  - **email**
  - **ФИО**
  - страна
  - город
  - место работы, учёбы
  - должность, учёная степень
  - номер телефона
  - **название доклада**
  - **аннотация**
  - **ключевые слова**
  - **выбор секции**
  - текст доклада (доступно после подтверждения заявки и отметки о выступлении)
2. Пользователь получает на email подтверждение регистрации и данные для входа в личный кабинет
3. Заявка ожидает подтверждения Администратором

### Управление своими заявками - ManageOwnApplications
*Sea level*

Главный успешный сценарий:
1. Пользователь авторизуется в системе
2. Пользователь просматривает свои заявки
3. Пользователь может:
  - отправить запрос на изменение/удаление подтверждённой заявки
  - добавить текст доклада *(plain text, LaTeX)*

### Просмотр информации о мероприятии - BrowseEvents
*Sea level*

Главный успешный сценарий:
1. Пользователь открывает сайт
2. Пользователь выбирает мероприятие, просматривает информацию о нём и список подтверждённых заявок по секциям

### Просмотр сертификата - CheckCertificate
*Sea level*

Главный успешный сценарий:
1. Пользователь открывает сайт
2. Пользователь вводит номер сертификата участника
3. Пользователь просматривает информацию о сертификате

### Подписка на мероприятие - SubscribeToEvent
*Fish level*

Главный успешный сценарий:
1. Пользователь авторизуется в системе
2. Пользователь выбирает мероприятия, которые ему интересны
3. Пользователь получает уведомления о мероприятиях:
  - информационные письма (сразу)
  - программа - список секций, список участников и темы докладов (за неделю до даты проведения)

### Подписка на доклады - SubscribeToPresentation
*Fish level*

Главный успешный сценарий:
1. Пользователь авторизуется в системе
2. Пользователь выбирает мероприятие, просматривает информацию о нём и список подтверждённых заявок по секциям
3. Пользователь выбирает заявки, которые ему интересны
4. После формирования окончательного списка заявок система отправляет покупателю список выбранных заявок с указанием информации о секции (название, место проведения) и приблизительного времени начала докладов по выбранным заявкам
