# goit-js-hw-05

About Репозиторий по выполнению ДЗ №5 JavaScript

# Задание 1

function-constructor Напиши функцию-конструктор Account, которая создает объект
со свойствами login и email.

В prototype функции-конструктора добавь метод getInfo(), который возвращает
строку со значениями свойств login и email объекта.

```js
// Write code under this line

//console.log(typeof Account.prototype.getInfo);
// 'function'

// const mango = new Account( 'Mangozedog', 'mango@dog.woof');
//console.log(mango.getInfo());
// 'login : Mangozedog, email: mango@dog.woof'

// const poly = new Account( 'Poly', 'poly@mail.com');
//console.log(poly.getInfo());
// 'login : Poly, email: poly@mail.com'
```

# Задание 2

class Напиши класс User для создания пользователя со следующим свойствами:

0. name - строка
1. age - число
2. followers - число

Добавь метод getInfo(), который, выводит строку: User ${имя} is ${возраст} years
old and has \${кол-во фоловеров} followers

```js
// Write code under this line

// console.log(typeof User);
// 'function'

// const mango = new User('Mango', 2, 20);
// console.log(mango.getInfo());
// 'User Mango is 2 years old and has 20 followers'

// console.log(typeof mango.getInfo);
// 'function'

// const poly = new User( 'Poly', 3, 17);
// console.log(poly.getInfo());
// 'User Poly is 3 years old and has 17 followers'
```

# Задание 3

использование методов класса Напиши класс Storage, который будет создавать
объекты для управления складом товаров. При вызове будет получать один
аргумент - начальный массив товаров, и записывать его в свойство items.

Добавь методы класса:

0. getItems() - возвращает массив текущих товаров
1. addItem(item) - получает новый товар и добавляет его к текущим
2. removeItem(item) - получает товар и, если он есть, удаляет его из текущих

```js
// Write code under this line

// console.log(typeof Storage);
// 'function'

const goods = ['Нанитоиды', 'Пролонгер', 'Железные жупи', 'Антигравитатор'];

// const storage = new Storage(goods);

// console.log(storage.getItems());
/* [
  'Нанитоиды',
  'Пролонгер',
  'Железные жупи',
  'Антигравитатор'
] */

// storage.addItem('Дроид');
// console.log(storage.getItems());
/* [
  'Нанитоиды',
  'Пролонгер',
  'Железные жупи',
  'Антигравитатор',
  'Дроид'
] */

// storage.removeItem('Пролонгер');
// console.log(storage.getItems());
/* [
  'Нанитоиды',
  'Железные жупи',
  'Антигравитатор',
  'Дроид'
] */
```

# Задание 4

```js

```

# Задание 5

```js

```
