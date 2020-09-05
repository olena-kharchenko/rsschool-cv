###Junior Developer Resume

**Yelena Kharchenko**

**Contact Info**

**_e-mail:_** harchenko.es1990@gmail.com

**_Summary_**
(your goal, wishes, reveal what is important for you, what do you want and why.
Some kind of self-presentation. In case of lack of experience Junior Developer sells his/her potential, his/her passion and ability to learn fast. You shouldn't think that everybody is going to teach you when you come to the workplace . Rather being a Junior means always
learning new things from everywhere etc.).

**_Skills_**
_Tech skills_

- HTML5
- CSS3
- GIT
- WebPack
- JavaScript
- React.js
- Node.js
  _Soft skills_
- Scrum
- Agile
- GTD
- Teamwork

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
(for a Junior Dev it means all kinds of experience: coding tests, projects from courses,
freelance projects - wherever they had the opportunity to demonstrate skills they have.
Also it would be awesome if you add links to source code)

**_Education_**

_Donetsk National Technical University_
_Land management and cadastre_
Septermber 2007 - January 2013 | Ukraine

**_English_**
(elaborate on what kind of practice you had, if any, how long it lasted and so on)
