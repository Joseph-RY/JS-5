# JavaScript

**Содержание**
- **[Строка (String)]()**
- **[Методы (Methods)]()**
- **[Числа (Number)]()**

---

![js.img](https://scrimba.com/articles/content/images/2022/09/Master-JavaScript-strings-with-real-world-examples-1.png)

## Строка (String).

### Что такое строка?

*- это понятие в языках програмирования принято считать за тип данных **[(DataType)]()**. Это означает что заданное значение является текстом(строка), от сюда и такое название.*

**ПРИМЕР:**

```JavaScript

let simpleString = `Hello World`;

console.log(simpleString) // Hello World - Строка / String

```

#### Варианты создания:

- Двойные ковычки ``` "Simple Text" ```
- Одиночные ковычки ``` 'Simple Text' ```
- Обратные ковычки (гравис) ``` `Simple Text` ```

##### Обратные ковычки (гравис) ``` ` ` ```

*- этот вариант имеет небольшое преимущество перед другими вариантами создания. Преимущество в том что во время присвоения значения можно добавить по среди текста другие элементы, такие как переменные, функции, массивы и т.п.Это вариант называется - backticks*

**ПРИМЕР:**

```JavaScript

let world = "World"
let backticks = `Hello ${world}`

console.log(backticks); // Hello World

```

---

![js.img](https://refine-web.imgix.net/blog/2022-11-02-js-every/social-2.png?w=1788)

## Методы (Methods)

### Что такое метод?

*Метод - это блок кода который выполняет определённую функцию каждый раз при вызове. Метод можно считать уже заранее подготовленные функции которые будут работать точно таким же образом. Они уже заложены в JS и поэтому для их инициализации достаточно обратится к ним.*

![](https://www.scaler.com/topics/images/what-is-method-in-javascript-thumbnail.webp)

---

## Примеры методов String

- ``` charAt() ``` метод возвращающий элемент указанного индекса.

```JavaScript

let text = "HELLO";

console.log(text.charAt(4)) // 'O'
console.log(text.charAt(0)) // 'H'

```

---

- ``` to.String() ``` метод возвращающий представленный элемент в качестве строки. Обычно не принимает аргументы.

```JavaScript

let number = 99 // Тип данных number

console.log(typeof number) // number
console.log(number.toString()) // 99
console.log(typeof number) // string

```