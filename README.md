# String_-_numbers 

---

<div align="center">
  <img src="https://media.proglib.io/wp-uploads/2017/08/1-OF0xEMkWBv-69zvmNs6RDQ.gif" alt="gifka">
</div>

---

# 📜 Работа со строками в JavaScript
*В JavaScript строки (string) — это один из основных типов данных. Они представляют текстовые значения и включают множество полезных методов для работы с текстом.*

```js
const str = "Hello, JavaScript!";
```

# 🔑 Основные свойства строк
*Длина строки: доступ через свойство length.*
```js
const str = "Hello";
console.log(str.length); // 5
```

# 🔧 Полезные методы строк
### toUpperCase() и toLowerCase()
*Изменение регистра строки.*
```js
const text = "Hello World!";
console.log(text.toUpperCase()); // "HELLO WORLD!"
console.log(text.toLowerCase()); // "hello world!"
```

### trim()
*Удаляет пробелы в начале и конце строки.*
```js
const spaced = "   JavaScript   ";
console.log(spaced.trim()); // "JavaScript"
```

### slice(start, end)
*Возвращает часть строки.*
```js
const str = "JavaScript";
console.log(str.slice(0, 4)); // "Java"
console.log(str.slice(-6));  // "Script"
```

### includes()
*Проверяет наличие подстроки.*
```js
const str = "Learning JavaScript";
console.log(str.includes("Java")); // true
console.log(str.includes("Python")); // false
```

### replace()
*Заменяет часть строки на другую.*
```js
const str = "I like JavaScript.";
console.log(str.replace("like", "love")); // "I love JavaScript."
```

> 💡 Совет: Для глобальной замены используйте регулярное выражение с флагом g.
```js
const str = "JavaScript is great. JavaScript is powerful.";
console.log(str.replace(/JavaScript/g, "JS")); 
// "JS is great. JS is powerful."
```

### split()
*Разбивает строку на массив.*
```js
const str = "apple,banana,kiwi";
console.log(str.split(",")); // ["apple", "banana", "kiwi"]
```
### charAt(index) и charCodeAt(index)
*Возвращает символ или код символа по указанному индексу.*
```js
const str = "ABC";
console.log(str.charAt(1)); // "B"
console.log(str.charCodeAt(1)); // 66
```

### repeat()
*Повторяет строку указанное количество раз.*
```js
const str = "JS ";
console.log(str.repeat(3)); // "JS JS JS "
```

### startsWith() и endsWith()
*Проверяет, начинается или заканчивается строка определённой подстрокой.*
```js
const str = "Frontend Developer";
console.log(str.startsWith("Front")); // true
console.log(str.endsWith("Developer")); // true
```



---

<div align="center">
  <img src="https://a.d-cd.net/fGkj61MC91njUbKjZUahzEm1-IA-960.jpg" width="600px" height="300px">
</div>

---
