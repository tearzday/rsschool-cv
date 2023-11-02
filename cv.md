# __Daniil Biver__ 

## __Contacts__
- __Location:__ Russia, Saint-Petersburg
- __Telegram:__ tearzday
- __Email:__ biverdaniil@gmail.com
- __GitHub:__ [tearzday](https://github.com/tearzday)

## __About Me__
I'm 23 years old. More than 2 years working on the position of HTML layout in different advertising agencies. My goal is to move to the position of Frontend-developer and improve my skills. In addition to work, I have a specialized higher education, as well as a number of different courses.
In addition to work I have various hobbies. For example, in my free time I am fond of sewing, go to the gym and am interested in various monetary investments (stocks, bonds, etc.).

## __Skills__
__Development languages (Web):__
- HTML
- CSS/SASS
- JavaScript

__Frameworks:__
- Vue 3
- Vutify 3
- Bootstrap

__Databases:__
- PostgresSQL
- MongoDB

__Other:__
- Axios
- NodeJS
- NPM
- Git
- ESLint

__Methodologies:__
- BEM
- OOP
- SOLID
- MVC

__Platforms:__
- VS Code
- Figma / Photoshop

__Languages studied at university:__
- Python
- C, C#
- Assembler
- 1С
- PHP
- SQL


## __Code Example__

DESCRIPTION:
Trolls are attacking your comment section!

A common way to deal with this situation is to remove all of the vowels from the trolls' comments, neutralizing the threat.

Your task is to write a function that takes a string and return a new string with all vowels removed.

For example, the string "This website is for losers LOL!" would become "Ths wbst s fr lsrs LL!".

Note: for this kata y isn't considered a vowel.

```
function disemvowel(str) {
  let vowels = 'aeiou';
  let resultStr = '';
  for(let i = 0; i < str.length; i++){
    switch(str[i]){
        case 'a':break;
        case 'e':break;
        case 'i':break;
        case 'o':break;
        case 'u':break;
        case 'A':break;
        case 'E':break;
        case 'I':break;
        case 'O':break;
        case 'U':break;
        default: resultStr += str[i]
    }
  }
  return resultStr;
}
```