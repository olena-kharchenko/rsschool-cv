#### Junior Developer Resume

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

**_Experience_**

- https://olena-kharchenko.github.io/rezume/
- https://zhivotenkoalex.github.io/barbershop/ (teamwork)
- https://olena-kharchenko.github.io/goit-markup-hw-08/
- https://olena-kharchenko.github.io/shaun/
- https://olena-kharchenko.github.io/doors/

**_Education_**

- _Donetsk National Technical University_
  (Land management and cadastre, Septermber 2007 - January 2013 | Ukraine)
- _Courses GOIT_
- _freecodecamp_

**_English_**
English at A2 level according to the test
