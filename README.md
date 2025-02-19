# Курс Яндекс Практикума: "Инженер по тестированию"
## Спринт 1: Тестирование веб-приложений
<details>
<summary> Содержание </summary>  

### Предисловие:
Яндекс Маршруты — сервис, который строит маршруты для транспорта разных видов, рассчитывает время и стоимость поездки. 
В рамках итогового проекта спринта предстоит подготовить тестовый набор и протестировать часть функциональности этого приложения: валидацию полей ввода времени и адресов, и логику расчета стоимости и времени поездки на собственном автомобиле.

### Материалы:
- [Требования и макеты на валидацию полей к Яндекс Маршрутам](https://docs.google.com/document/d/1tIs3KqK79vGR60EoGiDKLavvgsj0cjjrdSRK3AFdY6g)
- [Приложение Яндекс Маршруты](https://qa-routes.praktikum-services.ru/)

### Инструменты:
- Microsoft Excel 
- Тренажёр Яндекс.Практикум

### Задачи:
<details>
<summary> Тестирование валидации полей в форме </summary> 

***

1. Провести тест-анализ требований на валидацию полей. Если найдёшь серые зоны, обратись за разъяснением к преподавателю.
2. Создать набор тест-кейсов на проверку валидации полей формы Яндекс Маршрутов. Примени техники тест-дизайна: классы эквивалентности и граничные значения.
3. Протестировать валидацию полей и завести баг-репорты, если есть баги.

***

</details>

<details>
<summary> Тестирование расчета стоимости и времени поездки на собственном автомобиле </summary> 

***

1. Провести тест-анализ требований расчёта времени и стоимости маршрута на собственном автомобиле. Если найдёшь серые зоны, обратись за разъяснением к преподавателю.
2. Применить технику тест-дизайна «Классы эквивалентности» и создать набор тест-кейсов на проверку правильности расчета времени и стоимости поездки на собственном автомобиле.
3. Протестировать расчеты и завести баг-репорты, если есть баги.

***

</details>

### Процесс работы:

<details>
<summary> 1 Тестирование валидации полей в форме </summary> 

##### 1.1 Провести тест-анализ требований на валидацию полей:
- [Тест-анализ(без выделения цветом)](https://docs.google.com/spreadsheets/d/1R2X8VanBO6zNska67aCxbNWuKUFtL_dWRNr8Namsnn4/edit?gid=1610041137#gid=1610041137)

##### 1.2 Создать набор тест-кейсов на проверку валидации полей формы Яндекс Маршрутов. Примени техники тест-дизайна: классы эквивалентности и граничные значения:
- [Классы эквивалентности и граничные значения(без выделения цветом)](https://docs.google.com/spreadsheets/d/1R2X8VanBO6zNska67aCxbNWuKUFtL_dWRNr8Namsnn4/edit?gid=1304990855#gid=1304990855)

- [Наборы тест-кейсов(без выделения цветом)](https://docs.google.com/spreadsheets/d/1R2X8VanBO6zNska67aCxbNWuKUFtL_dWRNr8Namsnn4/edit?gid=1524919368#gid=1524919368)

##### 1.3 Протестировать валидацию полей и завести баг-репорты:
- [Баг-репорты(без выделения цветом)](https://docs.google.com/spreadsheets/d/1R2X8VanBO6zNska67aCxbNWuKUFtL_dWRNr8Namsnn4/edit?gid=454479584#gid=454479584)

***

</details>

<details>
<summary> 2 Тестирование расчета стоимости и времени поездки на собственном автомобиле </summary> 

##### 2.1 Провести тест-анализ требований расчёта времени и стоимости маршрута на собственном автомобиле:
- [Тест-анализ(выделено синим цветом)](https://docs.google.com/spreadsheets/d/1R2X8VanBO6zNska67aCxbNWuKUFtL_dWRNr8Namsnn4/edit?gid=1610041137#gid=1610041137)

##### 2.2 Применить технику тест-дизайна «Классы эквивалентности» и создать набор тест-кейсов на проверку правильности расчета времени и стоимости поездки на собственном автомобиле:
- [Классы эквивалентности и граничные значения(выделено синим цветом)](https://docs.google.com/spreadsheets/d/1R2X8VanBO6zNska67aCxbNWuKUFtL_dWRNr8Namsnn4/edit?gid=1304990855#gid=1304990855)

- [Наборы тест-кейсов(выделено синим цветом)](https://docs.google.com/spreadsheets/d/1R2X8VanBO6zNska67aCxbNWuKUFtL_dWRNr8Namsnn4/edit?gid=1524919368#gid=1524919368)
##### 2.3 Протестировать расчеты и завести баг-репорты, если есть баги:
- [Баг-репорты(выделено синим цветом)](https://docs.google.com/spreadsheets/d/1R2X8VanBO6zNska67aCxbNWuKUFtL_dWRNr8Namsnn4/edit?gid=454479584#gid=454479584)

***

</details>

***

</details>

## Спринт 2 Расширенное тестирование веб-приложений
<details>
<summary> Содержание </summary> 

### Предисловие:
Текущая версия Яндекс Маршрутов отличается от версии из первого спринта. Теперь в приложении можно заказать каршеринг. 
Предстоит протестировать каршеринг: составить тестовую документацию, выполнить проверки, завести баг-репорты.

### Материалы:
- [Макеты функциональности Каршеринг в веб-приложении Яндекс Маршруты](https://www.figma.com/design/42mNwme0cBfZwNZUIcN1mh/%D0%AF%D0%BD%D0%B4%D0%B5%D0%BA%D1%81.%D0%9C%D0%B0%D1%80%D1%88%D1%80%D1%83%D1%82%D1%8B?node-id=2-18586&p=f&t=FqWBPojLhspxVVL5-0)
- [Требования к функциональности Каршеринг в веб-приложении Яндекс Маршруты](https://praktikum.notion.site/74dd6e68fda34387ac4d43137a601c6e)

### Инструменты:
- Microsoft Excel 
- Тренажёр Яндекс.Практикум
- Figma
- YouTrack
- DevTools

### Задачи:
<details>
<summary> Подготовить чек-лист на вёрстку полей </summary> 

***

- форма бронирования;
- элементы на навигационной карте: это иконки автомобилей и действия с ними.

***

</details>

<details>
<summary> Подготовить чек-лист и тест-кейсы на логику работы окон </summary> 

***

- чек-лист на логику окон «Способ оплаты» и «Добавление карты»;
- тест-кейсы на кнопку «Забронировать».

***

</details>

<details>
<summary> Протестировать приложение и завести баг-репорты </summary> 

***

- проверить приложение по своей документации;
- создать баг-репорты в YouTrack и скопировать ссылки на них в свою таблицу.

***

</details>

### Процесс работы:
<details>
<summary> 1 Подготовка чек-листа на вёрстку полей </summary> 

***

##### 1.1 форма бронирования, элементы на навигационной карте: это иконки автомобилей и действия с ними:
- [Чек-лист](https://docs.google.com/spreadsheets/d/1HgR-ElM7J6nnU6Z4ZzNECNFt1CZEpAajLHopeOJQrz0/edit?gid=899462569#gid=899462569)

***

</details>

<details>
<summary> 2 Подготовить чек-лист и тест-кейсы на логику работы окон </summary> 

***

##### 2.1 чек-лист на логику окон «Способ оплаты» и «Добавление карты»:
- [Чек-лист](https://docs.google.com/spreadsheets/d/1HgR-ElM7J6nnU6Z4ZzNECNFt1CZEpAajLHopeOJQrz0/edit?gid=1540435533#gid=1540435533)

##### 2.2 тест-кейсы на кнопку «Забронировать»:
- [Тест-кейсы](https://docs.google.com/spreadsheets/d/1HgR-ElM7J6nnU6Z4ZzNECNFt1CZEpAajLHopeOJQrz0/edit?gid=1567345705#gid=1567345705)

***

</details>

<details>
<summary> 3 Протестировать приложение и завести баг-репорты </summary> 

***

##### 3.1 баг-репорты в YouTrack:
- [Баг-репорты](https://dmitrymalichenko.youtrack.cloud/issues?q=%D1%82%D0%B5%D0%B3:%20%7BSprint%202%7D)
- [Ссылка на папку со скриншотами](https://disk.yandex.ru/client/disk/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%D1%8B%2C%20%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%202%20%D1%81%D0%BF%D1%80%D0%B8%D0%BD%D1%82%D0%B0%20%D0%9C%D0%B0%D0%BB%D0%B8%D1%87%D0%B5%D0%BD%D0%BA%D0%BE%20%D0%94%D0%BC%D0%B8%D1%82%D1%80%D0%B8%D0%B9%2019%20%D0%BA%D0%BE%D0%B3%D0%BE%D1%80%D1%82%D0%B0%20)


***

</details>

</details>

## Спринт 3: Тестирование мобильных приложений
<details>
<summary> Содержание </summary> 

### Предисловие:
Команда Яндекс Метро сделала рефакторинг мобильного приложения на Android — внесла правки в код. Чтобы выпустить новую версию, предварительно нужно: 
- протестировать те части продукта, которых коснулись изменения;
- провести регрессионное тестирование и убедиться, что новую версию можно заливать в стор.

### Материалы:
- [Текущая версия приложения, которую пользователи скачивают из стора](https://code.s3.yandex.net/qa/files/yandexmetro-android-v2.13.apk)
- [Готовящаяся сборка](https://code.s3.yandex.net/qa/files/yandexmetro-android-v3.6.apk)
- [Требования к Яндекс Метро](https://code.s3.yandex.net/qa/files/Yandex_metro.pdf)

### Инструменты:
- Microsoft Excel 
- Тренажёр Яндекс.Практикум
- Figma
- Эмулятор Android Studio

### Задачи:
<details>
<summary> Подготовка к функциональному тестированию </summary> 

***

Требования, которые затронул рефакторинг приложения, выделили полужирным шрифтом. Теперь нужно написать к ним тесты.  Оформи проверки в виде чек-листа.

***

</details>

<details>
<summary> Подготовка к регрессионному тестированию </summary> 

***

Кроме проверок функциональности, затронутой рефакторингом, нужно провести регрессионное тестирование. Для этого напиши чек-лист, который учитывает особенности мобильного приложения: 
- Определи, какая функциональность Яндекс Метро взаимодействует с мобильным устройством.
- Зафиксируй мобильные проверки, которые связаны с этой функциональностью.
- Учти проверки, которые необходимы для любого мобильного приложения — например, тестирование обновления.

***

</details>

<details>
<summary> Выполнение тестирования </summary> 

***

- Протестируй мобильное приложение по своим чек-листам.
- Заведи баг-репорты в YouTrack.

По итогам прошлого релиза команда определила, на каком устройстве возникает больше всего багов. Поэтому сейчас решили тестировать именно на этой конфигурации: Honor 8, ОС Android 9.0 Pie, разрешение экрана 1080х1920, диагональ 5.5. Важно: тестирование необходимо провести на эмуляторе Android Studio. 

***

</details>

### Процесс работы:
<details>
<summary> Подготовка к функциональному тестированию </summary> 

***

##### [Чек-лист](https://docs.google.com/spreadsheets/d/1eb03C9QFL23b0MsSWPKyrKP-evsw9jMdq-3zoHfxFTs/edit?gid=899462569#gid=899462569)

***

</details>

<details>
<summary> Подготовка к регрессионному тестированию </summary> 

***

##### [Чек-лист](https://docs.google.com/spreadsheets/d/1eb03C9QFL23b0MsSWPKyrKP-evsw9jMdq-3zoHfxFTs/edit?gid=1540435533#gid=1540435533)

***

</details>

<details>
<summary> Выполнение тестирования </summary> 

***

##### [Баг-репорты](https://docs.google.com/spreadsheets/d/1eb03C9QFL23b0MsSWPKyrKP-evsw9jMdq-3zoHfxFTs/edit?gid=1261545000#gid=1261545000)


***

</details>

</details>

## Спринт 4 Тестирование API
<details>
<summary> Содержание </summary> 

### Предисловие:
Разработчики сделали новую функциональность в API Яндекс.Прилавка. Новую версию API передали на тестирование. 
- Работа с наборами: возможность добавлять продукты в набор — ручка POST /api/v1/kits/{id}/products.
- Работа с курьерами: возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит. Ручка POST /fast-delivery/v3.1.1/calculate-delivery.xml. 
- Работа с корзиной:
возможность получить список продуктов, которые добавили в корзину. Ручка GET /api/v1/orders/:id;
возможность добавлять продукты в корзину. Ручка PUT /api/v1/orders/:id;
возможность удалять корзину. Ручка DELETE/api/v1/orders/:id.

### Материалы:
- Тестовый стенд (с запуском сервера в тренажере Яндекс Практикума): https://{id}.serverhub.praktikum-services.ru/ 
- Документация API (с запуском сервера в тренажере Яндекс Практикума): https://{id}.serverhub.praktikum-services.ru/docs/
- [Требования к бэкенду](https://code.s3.yandex.net/qa/files/backend_requirements.pdf)

### Инструменты:
- Microsoft Excel 
- Тренажёр Яндекс.Практикум
- Postman
- Apidoc

### Задачи:
- Проанализируй требования к новой функциональности бэкенда Яндекс.Прилавка. Изучи документацию к API в Apidoc.
- Спроектируй тесты в виде чек-листа, чтобы покрыть функциональность, которую тебе передали на тестирование: она описана выше. Авторизацию проверять не нужно.
- Протестируй API через Postman и заведи баг-репорты, если это понадобится.

### Процесс работы:
<details>
<summary> Проектирование чек-листов </summary> 

***

##### [Чек-лист](https://docs.google.com/spreadsheets/d/1kChXJKP_KU-1-q0ofxTkGQDR6JTCTKuG2hE2zmrGfQA/edit?gid=2006427015#gid=2006427015)

***

</details>

<details>
<summary> Тестирование API через Postman </summary> 

***

##### [Баг-репорты](https://docs.google.com/spreadsheets/d/1kChXJKP_KU-1-q0ofxTkGQDR6JTCTKuG2hE2zmrGfQA/edit?gid=797418779#gid=797418779)

***

</details>

</details>

## Дипломный проект. Тестирование приложения Яндекс Самокат веб-приложение, мобильное приложение, API
<details>
<summary> Содержание </summary> 
  
### Что нужно сделать
- Обрати внимание: тестировать нужно не всё приложение целиком. Изучи, что именно предстоит проверить.
- Изучи документацию к приложению в каждом задании. Она хранится в виде списка требований и макетов, а также требований к URL-адресам, которым приложение отправляет данные.
- Разбей функциональность на атомарные блоки, определи объекты тестирования.
- Спроектируй тесты, чтобы покрыть все требования. Примени техники КЭ и ГЗ, а также таблицу принятия решений там, где это нужно.
- Оптимизируй количество проверок в UI-тестах и тестах на логику работы функциональности.
- Проведи тестирование и заведи баг-репорты, если нужно.
- Чтобы проверить обращения к определённому URL, пользуйся DevTools, Charles или Postman.

### Техническая информация при запуске сервера приложения в тренажере Яндекс Практикум (Информация меняется после каждого перезапуска сервера)
- Имя пользователя: 62b960de-1d5f-4928-ac2a-46944ee3504a
- Хост: serverhub.praktikum-services.ru
- Порт: 4554
- Тестовый стенд веб-приложения: https://62b960de-1d5f-4928-ac2a-46944ee3504a.serverhub.praktikum-services.ru/
- Документация API: https://62b960de-1d5f-4928-ac2a-46944ee3504a.serverhub.praktikum-services.ru/docs/
- Чтобы авторизоваться в мобильном приложении, нужно создать курьера. Чтобы создать курьера, изучи документацию к API. Не забудь - параметры для метода post передаются в body запроса с типом json.
- При тестировании мобильного приложения, чтобы настроить мобильное приложение на взаимодействие с бэкендом, кликни по значку «?» на главном экране в правом нижнем углу. Появится окно ввода: укажи адрес подключения к API: https://62b960de-1d5f-4928-ac2a-46944ee3504a.serverhub.praktikum-services.ru и нажми «Ок».
- URL, который нужно использовать в запросах к API: https://62b960de-1d5f-4928-ac2a-46944ee3504a.serverhub.praktikum-services.ru
- Логи лежат в файле error.log в папке /var/www/backend/logs
- Доступ к базе осуществляется с помощью команды psql -U morty -d scooter_rent. Пароль: smith.

### Материалы:
- [Требования к веб-приложению (после запуска сервера в тренажере Яндекс Практикума)](https://code.s3.yandex.net/qa/files/requirements_web_app_1.1.pdf)
- [Макеты веб-приложение](https://www.figma.com/file/vHgTVzFac8zyxhMZ2o4b2m/web)
- [Тестовый стенд веб-приложения](https://62b960de-1d5f-4928-ac2a-46944ee3504a.serverhub.praktikum-services.ru/)
- [Требования к мобильному приложению](https://code.s3.yandex.net/qa/files/requirements_mob_app.pdf)
- [Макеты мобильного приложения](https://www.figma.com/file/kqLqPvSvjLVLomkdadkAnk/mobile)
- [Тестовая сборка МП](https://code.s3.yandex.net/qa/files/scooter-v2.0.apk)
- [Требования к бэкенду](https://code.s3.yandex.net/qa/files/requirements_backend.pdf)
- [Документация API](https://62ec410c-c751-4ba2-816a-b90cbf03e1a9.serverhub.praktikum-services.ru/docs/)
- URL запросов к API(после запуска сервера в тренажере Яндекс Практикума) - https://62b960de-1d5f-4928-ac2a-46944ee3504a.serverhub.praktikum-services.ru

### Инструменты:
- Microsoft Excel 
- Тренажёр Яндекс.Практикум
- Postman
- Apidoc
- DevTools
- Charles
- Figma

### Задачи:
<details>
<summary> Задание 1: тестирование веб-приложения Яндекс.Самокат </summary> 

***

- Обрати внимание на техническую информацию при запуске сервера приложения в тренажере Яндекс Практикум. — в ней описаны все доступы к серверу, БД и адреса API.
- Изучи требования.
- Составь чек-лист по требованиям к экрану «Статус заказа».
- Для экрана «Сделать заказ» составь проверки на валидацию полей. Заполни их в виде таблицы по шаблону.
- Проведи тестирование всей функциональности не только по получившимся чек-листам и таблицам, но и по остальным макетам и требованиям. Проверять главную страницу (лендинг) не нужно. Макеты лежат в Figma Результаты помести на вкладку «Задание 1: баги вне тестовой документации».

***

</details>

<details>
<summary> Задание 2: тестирование мобильного приложения Яндекс.Самокат </summary> 

***

- Обрати внимание на техническую информацию при запуске сервера приложения в тренажере Яндекс Практикум.
- Изучи требования к приложению.
- Спроектируй тест-кейсы и протестируй функциональность, которая выделена жирным шрифтом. Не забудь написать кейсы и на вёрстку по макетам к этой функциональности. Макеты лежат в Figma.

***

</details>

<details>
<summary> Задание 3: тестирование API Яндекс.Самокат </summary> 

***

- Обрати внимание на техническую информацию при запуске сервера приложения в тренажере Яндекс Практикум.
- Изучи требования к бэкенду и документацию к API.
- Разработай чек-лист и протестируй API по требованиям, которые выделены жирным шрифтом.

***

</details>

### Процесс работы:
<details>
<summary> Задание 1: тестирование веб-приложения Яндекс.Самокат </summary> 

***

- [Чек-лист по требованиям к экрану «Статус заказа»](https://docs.google.com/spreadsheets/d/1ecIrtoaHAJSNwUp8akYjMQ8qqS8SlJeu_oev9DPzrs8/edit?gid=943703744#gid=943703744)
- [Проверки экрана «Сделать заказ» на валидацию полей](https://docs.google.com/spreadsheets/d/1ecIrtoaHAJSNwUp8akYjMQ8qqS8SlJeu_oev9DPzrs8/edit?gid=1540465171#gid=1540465171)
- [Баги вне тестовой документации](https://docs.google.com/spreadsheets/d/1ecIrtoaHAJSNwUp8akYjMQ8qqS8SlJeu_oev9DPzrs8/edit?gid=1539613303#gid=1539613303)
- [Баг-репорты](https://docs.google.com/spreadsheets/d/1d8FDF9wREn8jQRRrpTaDsiEzJ29kTa1lguBQGkhwxvc/edit?gid=1186534874#gid=1186534874)

***

</details>

<details>
<summary> Задание 2: тестирование мобильного приложения Яндекс.Самокат </summary> 

***

- [Тест-кейсы](https://docs.google.com/spreadsheets/d/1ecIrtoaHAJSNwUp8akYjMQ8qqS8SlJeu_oev9DPzrs8/edit?gid=424948590#gid=424948590)
- [Баг-репорты](https://docs.google.com/spreadsheets/d/1d8FDF9wREn8jQRRrpTaDsiEzJ29kTa1lguBQGkhwxvc/edit?gid=1698427932#gid=1698427932)

***

</details>

<details>
<summary> Задание 3: тестирование API Яндекс.Самокат </summary> 

***

- [Чек-лист](https://docs.google.com/spreadsheets/d/1ecIrtoaHAJSNwUp8akYjMQ8qqS8SlJeu_oev9DPzrs8/edit?gid=336872680#gid=336872680)
- [Баг-репорты](https://docs.google.com/spreadsheets/d/1d8FDF9wREn8jQRRrpTaDsiEzJ29kTa1lguBQGkhwxvc/edit?gid=1587705626#gid=1587705626)

***

</details>
