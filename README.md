# Реализация функции bind

## Описание
Нужно написать функцию, которая будет реализовывать метод bind. Первый аргумент - функция, у которой закрепляем контекст. Второй - сам контекст. Все остальные аргументы – входные параметры для функции (первый аргумент).
Для того, чтобы рассмотреть все краевые случаи, поэкспериментируйте на настоящем методе bind. Посмотрите, как он работает.
Можно использовать все, кроме самого метода bind.

### Пример:
```js
/**
 * Создайте собственную реализацию функции bind
 * @param {Function} func передаваемая функция
 * @param {any} context контекст
 * @param {Array<any>} args массив аргументов
 * @return {Function} функция с нужным контекстом
 */
function customBind (func, context, ...args) {
    // code
}
```

# Функция sum

## Описание
Нужно написать функцию, которая будет работать как в примере ниже. Если первый вызов sum происходит без аргументов, результат будет – 0.

### Пример:
```js
/**
 * Напишите функцию sum, вычисляющую суммы подобным образом:
 * sum(1)(2)( ) // 3
 * sum(1)(2)(3)( ) // 6
 * sum :: Number -> sum
 * sum :: void -> Number
 */
function sum (x) {
}
```
