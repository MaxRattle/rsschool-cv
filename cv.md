#Максим Сушков

---

##Trainee Frontend Developer

---

##Контакты
####Телефон: +7-914-075-83-20
####Почта: max_123_99@mail.ru
####Соц. Сеть: [VK](https://vk.com/lilbrokenheart21)

---

###О себе:
Начал самостоятельно изучать веб-разработку 27.08.2023. До этого был опыт в изучении Python в 2021 году.
В силу обстоятельств я забросил изучение. Сейчас появилось время и я вновь начал изучать программирование.
Прошел несколько курсов на ютубе и скачанных. Работаю по специальности (не связанно с IT).
Почему я решил изучать программирование?
Во-первых это интересно, во-вторых дает ряд преимуществ (удаленная работа, перспективы развития, интересные задачи и высокая ЗП).

---

###Навыки:
####Soft Skills:

- Тактичность
- Умение слушать и договариваться
- Пунктуальность и взаимоуважение.

####Technical Skills:

- HTML+CSS: верстка, flex-box, grid, адаптив.
- JS: ES6, базовые знания (типы данных, области видимости итд.), DOM, ООП (не использовал, но понимания имеется).
- React: базовые hooks,components, JSX. (в целом подзабылось, на данном этапе прошел курс, но практикой не закрепил).
- GIT: базовые команды.

---

###Пример кода:

- JS:
  ЗАДАЧА 47 - Использование метода "reduce" для создания массива

1.  Создайте функцию "popularPostsIds" с двумя параметрами "posts" и "minimalComentsQty"

2.  Эта функция "popularPostsIds" должна возвращать массив идентификаторов постов сообщений,
    у которых количество комментариев не меньше "minimalComentsQty"

```
const inputPosts = [
 {
   title: "Как быстро выучить JavaScript?",
   postId: 3421,
   comments: 25,
 },
 {
   title: "Где используется JavaScript?",
   postId: 5216,
   comments: 3,
 },
 {
   title: "Какая разница между React и Angular?",
   postId: 8135,
   comments: 12,
 },
];
//решение
function popularPostsIds(posts, minimalComentsQty) {
 return posts.reduce(
   (postIds, commentIds) =>
     commentIds.comments >= minimalComentsQty
       ? postIds.concat([commentIds.postId])
       : postIds,
   []
 );
}
//проверка
console.log(popularPostsIds(inputPosts, 10)); // [3421, 8135]
console.log(popularPostsIds(inputPosts, 15)); // [3421]
console.log(popularPostsIds(inputPosts, 50)); // []
```

---

####Курсы:

- JavaScript - Полный Курс по JavaScript. (Автор: Bogdan Stashchuk)
- Фундаментальный JavaScript. (Автор: Михаил Непомнящий)
- React - Полный Курс по React. (Автор: Bogdan Stashchuk)
- [Современный учебник по JavaScript](https://learn.javascript.ru/)
- Курс Rs-School: JavaScript/Front-end 2023Q4 (в процессе)

---

####Языки:

- Русский (native)
- Английский (B1 по итогам обучения в качестве дополнительного образования при вузе)

---

//
####Личная информация:
| Имя/Фамилия | Максим Сушков |
-----------|:-------:
| Дата рождения | 21.02.1999 |
| Месторасположение | Россия, Приморский край, Большой Камень |

---
