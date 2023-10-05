# Приложение для проверки работы Go Api

Набор простых приложений для TODO

## Этапы

Фронт на Vue.js без поддержки Api

- [x] Шаблон Vue.js
- [x] Отображение Todo из списка
- [x] Возможность добавлять в список, удалять из списка
- [x] Сохранение состояния в локальное хранилище
- [ ] Стилизация отображения

Api на Golang

- [ ] Генерация моделей на основе proto
- [ ] Генерация методов API из proto
- [ ] Генерация swagger
- [ ] Реализация методов

Фронт на Vue.js с поддержкой Api
- [ ] Переработка методов для поддержки получения данных из API
- [ ] Разобраться с TS, переписать текущую реализацию на TS
- [ ] Стилизация состояний загрузки-добавления

TUI клиент на Go
- [ ] Генерация моделей из proto
- [ ] Создание шаблона приложения на Bubbletea
- [ ] Реализация страницы списка и страницы about
- [ ] Реализация методов для получения отправки TODO

Api на Golang - подключение базы
- [ ] реализовать репозиторий на sql