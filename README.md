# js-22

<!-- ! ASYNCHRONY -->

- Асинхронность в JavaScript
  - Однопоточность и многопоточность
  - Отоложенные вызовы (планирование)
  - Web workers для «многопоточности»
  - Service workers для «перехвата» запросов от документа (кеширование)
  - [Статья](https://bitsofco.de/web-workers-vs-service-workers-vs-worklets)
- Планирование: window.setTimeout() и window.setInterval()
- Цикл событий (event loop)
  - [Площадка](http://latentflip.com/loupe)
  - setTimeout(N) и setTimeout(0)
- Мастерская: оповещение
- Мастерская: «надоедалка» подписки
  - Bootstrap для CSS
  - Bootstrap Native для JS
- Встроенный объект Date
  - Создание
  - Разница времени
  - Date.now() и new Date().getTime()
  - [Библиотека date-fns](https://date-fns.org/)
- Мастерская: таймер

<!-- ! PROMISE -->

- Promise API
  - Promise.prototype.then(result)
  - Promise.prototype.catch(error)
  - Promise.prototype.finally()
- Цепочки промисов
- Промисификация функций
- Статические методы:
  - Promise.all()
  - Promise.race()
- Мастерская: ипподром
- Чтиво:
  - [Промисы на примере бургер-вечеринки](https://habr.com/ru/company/nix/blog/323066/)
  - [У нас проблемы с промисами](https://habr.com/ru/company/mailru/blog/269465/)

<!-- ! HTTP -->

# js-22

## [Часть 1 (теория)](https://docs.google.com/presentation/d/1YK1DogtkPz0zTo313uAeuvvNh1vFfbStCD-g39jGd5M/edit?usp=sharing)

- Архитектура клиент-сервер
  - Протоколы передачи данных: HTTP и HTTPS
  - REST API (backend)
  - Публичные REST API
- Допмат (видео):
  - [The World Wide Web](https://youtu.be/guvsH5OFizE?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo)
  - [How The Internet Works](https://www.youtube.com/playlist?list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7)

## Часть 2 (практика)

- HTTP-запросы в браузере
  - Fetch API
  - Владка Network
  - HTTP-методы
  - Заголовки
  - MIME-типы
  - [Параметры запроса](https://pixabay.com/api/docs/)
- Документация REST API
- Обработка 404 с fetch 🐷
- Аутентификация
  - [https://newsapi.org/](https://newsapi.org/)
  - [https://weatherstack.com/](https://weatherstack.com/)
  - [https://pixabay.com/api/docs/](https://pixabay.com/api/docs/)
- Библиотеки-обёртки
- [Отмена HTTP-запроса с AbortController](https://davidwalsh.name/javascript-promise-tricks)

## Часть 3

- Cross-Origin Resource Sharing (CORS)
  - [Статья на MDN](https://developer.mozilla.org/uk/docs/Web/HTTP/CORS)
  - [https://pokeapi.co/](https://pokeapi.co/)
  - [https://darksky.net/dev](https://darksky.net/dev)
- Proxy
  - Хранение API ключей и секретов
  - [https://lpj-weather-service.herokuapp.com/](https://lpj-weather-service.herokuapp.com/)

<!-- ! REST Pagination -->

- Пагинация REST API
  - Параметры запроса
    - «Страница»
    - Кол-во элементов в одной «странице»
- Пагинация на клиенте с кнопкой "Load more"
- Бесконечный скролл (выносим на Вопрос-ответ свободной недели)
  - [https://infinite-scroll.com/](https://infinite-scroll.com/)
