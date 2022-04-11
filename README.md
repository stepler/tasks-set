# Набор задач

Чтобы было не скучно)

## Требования

**ПО**

-   `Node.js v12+`
-   `Git`

**Знания**

-   Основы JS — [https://learn.javascript.ru/first-steps](https://learn.javascript.ru/first-steps)
-   Знание части TypeScript инструкций — [функции](https://www.typescriptlang.org/docs/handbook/2/functions.html) и [дженерики](https://www.typescriptlang.org/docs/handbook/2/generics.html).

## Задания

**Условия задач**\
Задачи сделаны с упором на чтение кода.
В них не расписаны условия, их можно извлечь из тестов которые рядом с заданиями.

**Сложность**\
Некоторые задачи содержат `base` и `improved` тесты.
Прохождение `improved` тестов требует более сложной реализации задачи.

**Пометка `in-place`**\
Задачи с пометкой `in-place` означает что функция не создает новую структуру данных, а меняет входную

## Процесс выполнения

1. Создать свою ветку\
   `git checkout <my-branch> && git push origin <my-branch>`

2. Решить часть задач и сделать ПР в свою ветку\
   **Важно!** Не подсматривать в чужие ветки, тут задача не в том чтобы все сделать правильно с первого раза.

3. Подтянуть новые задачи\
   `git fetch && git rebase origin/master && npm i`

4. Вернуться к пункту 2

## Будет полезно

**Ускоряемся**\
Чтобы не гонять все тесты разом, можно указать `npm test -- swap` чтобы запускались только тесты из `array/swap.test.ts` — [подробнее](https://jestjs.io/docs/cli#jest-regexfortestfiles).

А еще можно запускать `npm test -- --watch swap` чтобы тесты перезапускались при редактировании задачи.
