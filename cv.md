# Alexander Sultanov

#### *contacts*
- **Dicsord**: @Alexander
- **Telegram**: @ksandrsl
- **Email**: syltan21@gmail.com

#
#### *About me*
Sociable and cheerful, I love cooking and traveling. I want to become a front-end developer to have a remote job and the opportunity to travel even more!

#
#### *Basic Skills*
- HTML & CSS
- JS
- Git
- SASS
- Figma
- BEM methodology

#
#### *Code Examples*

Codewars task *Consecutive strings* solution:

```js
// You are given an array(list) strarr of strings and an integer k. 
// Your task is to return the first longest string consisting of k consecutive strings taken in the array.

// strarr = ["tree", "foling", "trashy", "blue", "abcdef", "uvwxyz"], k = 2
// Two strings are the longest: "folingtrashy" and "abcdefuvwxyz".
// The first that came is "folingtrashy" so 
// longest_consec(strarr, 2) should return "folingtrashy".

```js
function longestConsec(arr, k) {
  let longest = '';

  for (i = 0; i <= arr.length - k && k > 0; i++) {
      let str = arr.slice(i, i + k).join('');
      if (str.length > longest.length) longest = str;
  }

  return longest;
}
```

#
#### *Work Expirience*
- ... - 2012. Was engaged in various kinds of work that did not require experience, like many students
- 2012 - 2014. Worked as a bartender and barista in nightclubs, hotel and lounge bars
- 2014 - 2018. Engaged in construction, plaster casting and furniture production
- 2018 - 2023. Worked remotely as a support operator for an online store

#
#### *Education*
- Cooking college
- Some books about HTML & CSS
- Learning JS by [learn.javascript.ru](https://learn.javascript.ru/)
- I'm taking a Front-end course at [RS School](https://rs.school/)

#
#### *Languages*
- Russian - Native speaker
- English - B1 (Intermediate)