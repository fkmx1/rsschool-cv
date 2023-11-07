# __Maksim Pegov__

## __Contacts__
- __Location:__ Belarus
- __Phone:__ +375445346560
- __Email:__ makspegov25@gmail.com
- __GitHub:__ [Maksim Pegov](https://github.com/fkmx1)
- __Discord:__ Matr1x (@fkmx1)
- __Telegram:__ @fkmx1

## __About Me__
I'm studying frontend because I really like it and I want to become a professional in it. My strengths are diligence and discipline. I have a great desire to explore this world and learn new things.

## __Skills__
- HTML
- CSS/SCSS/SASS
- Gulp
- Git
- JavaScript
- Photoshop
- Figma

## __Example Code__
Write a function named first_non_repeating_letter that takes a string input, and returns the first character that is not repeated anywhere in the string.

For example, if given the input 'stress', the function should return 't', since the letter t only occurs once in the string, and occurs first in the string.

As an added challenge, upper- and lowercase letters are considered the same character, but the function should return the correct case for the initial letter. For example, the input 'sTreSS' should return 'T'.

If a string contains all repeating characters, it should return an empty string ("") or None -- see sample tests.

```
function firstNonRepeatingLetter(s) {
  let res = '';
  let array = s.toLowerCase();

    for (let value of array) {
    if (array.indexOf(value) === array.lastIndexOf(value)) {
      res = s[array.indexOf(value)];
      break;
    }
  }
  return res;
}
```

## __Education__
- __University:__ "Belarusian-Russian", Faculty of Engineering and Environmental Engineering. Specialization as a software engineer. Bachelor's degree 2018-2022
- __Courses:__
  - [HTML Academy](https://www.htmlacademy.ru)
  - [Code Basics](https://code-basics.com)

## __Experience__
- Academic projects at the university

## __Languages__
- English: B1
- Russian, Belarusian: native speaker