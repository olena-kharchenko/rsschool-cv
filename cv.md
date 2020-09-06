### Junior Developer Resume

## **Yelena Kharchenko**

**_Contact Info_**
**_e-mail:_** harchenko.es1990@gmail.com

**_Summary:_**
Javascript is my love. I want to code all day long

**_Skills_**

- _Tech skills_ (HTML5, CSS3, GIT, WebPack, JavaScript, React.js, Node.js)

- _Soft skills_ (Scrum, Agile, GTD, Teamwork)

**_Code examples_**

```
import { default as users } from './users.js';
console.table(users);

// Получить массив всех умений всех пользователей (поле skills), при этом не должно быть
// повторяющихся умений и они должны быть отсортированы в алфавитном порядке.

const getSortedUniqueSkills = array => {
[...array]
.reduce((acc, { skills }) => [...acc, ...skills], [])
.filter((value, index, array) => array.indexOf(value) === index)
.sort();

console.log(getSortedUniqueSkills(users));
```
