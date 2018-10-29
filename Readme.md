# Развёртка проекта
1. Установите зависимости `npm i`
2. Для запуска сервера `browser-sync` вызовите команду `npm start`
3. Для запуска сервера `browser-sync` с поддержкой потокового видео вызовите команду `npm run start-stream`
В обоих случаях браузер должен открыться автоматически.
Если этого не произошло, сервер должен быть доступен по адресу localhost:3000.

# Команды
  `npm start` — запуск сборки в режиме `develop` и тестового сервера
  `npm run start-stream` — запуск сборки И сервера потокового видео
  `npm run build` — сборка без запуска сервера
  `node-serv` — запуск сервера Node.js
  
# Комментарии к заданию "Типизация"

## Сложные моменты в работе
Самое сложное — подключить TS к существующей сборке. На подключение — около 5 часов, на саму типизацию — час.
Сейчас даже сложно вспомнить, в каком порядке валились ошибки, но началось всё с конфликтов с потоковым видео (в результате пришлось исключать папку streams).

## Ошибки, найденные в процессе
Никаких серьёзных ошибок выявлено не было, т.к. приложение работало корректно и без ошибок. Были закрыты некоторые незначительные "дыры", допускавшие падение приложения при маловероятных условиях.

## Предпочту остаться на чистом JS
Считаю типизацию избыточной для крохотного приложения, поддерживаемого одним человеком.
Однако же планирую использовать TS для крупных проектов и проектов с большим колличеством участников.
