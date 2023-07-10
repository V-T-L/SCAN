«СКАН» — система управления репутацией, созданная ведущим российским информационным агентством «Интерфакс». Сервис предназначен для менеджеров по PR, коммуникациям и специалистов по рискам и безопасности. Решает широкий спектр задач, связанных с медиааналитикой.

Система анализирует материалы СМИ и социальные медиа, оповещает о новых публикациях в режиме реального времени, автоматически формирует аналитические отчёты по любым запросам и инфоповодам, а также позволяет прогнозировать репутационные и экономические риски, связанные с партнёрами и контрагентами.

Проект реализован на фреймворке React.js + typescript, для навигации использовался react-router-dom, для хранения состояния redux, для стилей styled-components + библиотека компонентов antd design

Клиентская часть сервиса состоит из:

- главной страницы,
- формы авторизации,
- формы для ввода параметров запроса,
- страницы с выводом результатов запроса.

[Макет сайта в figma](https://www.figma.com/file/u3MOjzYnTnirz712GrLbFv/%D0%9C%D0%B0%D0%BA%D0%B5%D1%82-%D0%A1%D0%9A%D0%90%D0%9D?node-id=0-1&t=Cy1BF6b76dS4G8er-0)



Тестовый пользователь
user: sf_student9
password: k%3E%nJF9y

Описания работы сайта:
Не автаризованному пользователю доступны главная страница и страница входа, после авторизации с главной страницы можно перейти на страницу поиска.
После ввода данных открываеться страница с результатами и первыми 10 постами, по клику на кнопку внизу "Показать больше" загружаются следующиие 10.



## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
