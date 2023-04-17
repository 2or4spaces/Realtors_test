# Jilfond_test

## Для запуска проекта

1. Устанавливаем зависимости

```sh
npm install
```

2. Запускаем проект на localhost (по умолчанию порт 5173)

```sh
npm run dev
```

3. Необязательно. Для сборки и предпросмотра проекта используем

```sh
npm run build
npm run preview
```

## О приложении

Необходимо реализовать поиск сотрудников компании с обращением к тестовому API. Поиск должен выполняться как по ID сотрудника, так и по его имени. О результатах поиска нужно уведомить пользователя коротким сообщением. Во время обработки запроса появляется preloader. При клике на карточку найденного сотрудника, можно подробнее ознакомиться с его профилем в центральной части приложения. Двойной клик по карточке сотрудника удалет его из результатов поиска. Также реализована возможность полностью очистить результаты поиска с помощью отдельной кнопки.