![CI](https://github.com/JonS87/components/actions/workflows/web.yml/badge.svg)
Компоненты
===

Необходимо выполнить и предоставить на проверку следующие задачи:

1. [Страница интернет-магазина (функциональный компонент)](store-func).
1. [Страница интернет-магазина (class-based компонент)](store-class).
1. [Календарь](calendar) — необязательная задача со звёздочкой.

Любые вопросы по решению задач задавайте в группе в Discord.

Все три задачи лучше сдавать в разных репозиториях, то есть через create-react-app реализовать три проекта, чтобы не
было конфликта стилей. Но если вы позаботитесь о том, что конфликта не будет, то можете сдавать и в одном проекте.

Все стили необходимо размещать в файле App.css.

#### Альтернативный способ создания приложения React с использованием тулинга Vite

Приложение также можно создать используя инструмент Vite.
Документация по созданию приложения [React](https://vitejs.dev/guide/).

1. Откройте терминал и пропишите следующую команду: `yarn create vite my-app --template react`,
   либо `yarn create vite my-app --template react-ts`, если
   нужен шаблон с TypeScript. Эта команда создаст настроенный
   шаблонный проект.
2. Откройте созданный проект в своей IDE.
3. Установите зависимости.
4. Готово. Чтобы запустить приложение, введите команду: `yarn dev`(либо `npm run dev`).
  