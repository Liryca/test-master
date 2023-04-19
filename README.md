
Задание находится в процессе разработки


Тестовое задание

В качестве тестового задания мы предлагаем тебе реализовать небольшое приложение, в котором есть всего по чуть-чуть: вёрстки, работы с API, преобразования данных и т. д.

Обязательный стэк
Create React App
React Router
Axios
Рекомендуется дополнительно использовать
Typescript
Effector \ redux
styled-components

https://www.figma.com/file/GRRKONipVClULsfdCAuVs1/KODE-Trainee-Dev-Осень'21?node-id=11%3A14414

API
Спецификация метода API - https://kode-frontend-team.stoplight.io/docs/koder-stoplight/e981f97438300-get-users-list

Функциональные требования
Запуск
Когда пользователь открывает сайт, необходимо загрузить актуальный список всех работников компании.

При входе в приложение необходимо отобразить экран 2.0.0. Изначально он должен быть в состоянии загрузки, экран 1.0.0. Если при загрузке произошла ошибка, отсутствует интернет-соединение или API вернул ошибку, необходимо отобразить экран «Критическая ошибка». В случае успеха необходимо отобразить Top App Bar и список людей.

Top App Bar
Компонент находится вверху экрана и представляет собой поле для поиска с иконкой «Поиск», кнопкой «Сортировка» и панелью вкладок. При переключении между вкладками на главном экране список работников фильтруется и отображаются только люди, работающие в выбранном департаменте, либо все, если выбрана вкладка «Все».

Возможны 2 вида реализации
Простая. Использовать фильтрацию пользователей на клиенте.
Чуть сложнее. Использовать серверную фильтрацию по параметру __example
Задание со звёздочкой
Рассказать о преимуществах и недостатках способов реализации.

При нажатии на кнопку «Фильтр» открывается модальное окно с вариантами сортировки списка работников. Есть два варианта сортировки: «По алфавиту» (по умолчанию), «По дню рождения». При переключении варианта сортировки модальное окно должно закрываться, а список на главной странице должен обновиться.

Когда пользователь вводит текст в поисковое поле, необходимо фильтровать список на главном экране и отображать только работников, соответствующих параметрам поиска. Поиск может осуществляться по имени, фамилии или никнейму, состоящему из двух символов.

В случае отсутствия результатов поиска необходимо отобразить информацию о том, что ничего не было найдено. Экран "2.0.2Г Люди (Ошибка поиска)"

Страница «Главная»
На странице должна быть расположена верхняя панель приложения, на которой должны находиться:

поле для поиска;
панель вкладок для группировки загруженного списка пользователей;
список работников.
Список должен обновляться каждый раз, когда меняются параметры поиска, обновляется вариант сортировки или пользователь переключает вкладки департаментов.

Пользователь имеет возможность скроллить список работников.

В режиме сортировки «По алфавиту» для каждого работника отображается его фотография, имя, никнейм и департамент.

В режиме сортировки «По дню рождения» список отображается от ближайшей даты дня рождения вниз. Если день рождения следующего работника будет только в следующем году, то необходимо отобразить блок с годом, экран 2.0.1.

Когда пользователь кликнет на человека, необходимо открыть экран информации о человеке (экран «детали»).

Задание со звёздочкой
Поиск, обновление списка должно происходить только после того, как пользователь закончил печатать.

Страница «детали»
Должна быть реализована как отдельный роут в приложении.

Должна быть возможность попасть на страницу по ссылке.

Вверху экрана деталей должна отображаться кнопка назад для навигации на главный экран. Также можно вернуться на главный экран, если нажать кнопку назад в браузере.

В шапке экрана должна отображаться аватарка пользователя, имя, никнейм и название департамента. Ниже находится дата рождения и номер телефона. При нажатии на номер телефона необходимо открыть приложение для звонка по номеру.





