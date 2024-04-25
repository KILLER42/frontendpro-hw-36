# ДЗ 36. Hoisting

Нижче наведено кілька прикладів коду. Проаналізуйте і поясніть, що відбувається в кожному випадку, та який результат буде виведено в консоль.

Приклад 1:
```javascript
console.log(a);
 var a = 10; 

```
Приклад 2:

```
myFunction(); 

function myFunction() { 
    console.log('Hello, world!'); 
 } 

```

Приклад 3:
```
console.log(b); 
let b = 5; 

```

Приклад 5:
```
const myArrowFunction = () => { 
console.log('Hello from arrow function'); 
}

 myArrowFunction(); 

```

Написання Коду: 

Напишіть власні приклади коду, де:

В одному випадку hoisting призводить до успішного виконання коду.
В іншому випадку hoisting призводить до помилки. Поясніть, чому сталася помилка.
