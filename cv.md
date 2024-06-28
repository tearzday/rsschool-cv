# Biver Daniil

## Contacts for communication:

- **telegram:**  @tearzday
- **gmail:** biverdaniil@gmail.com
- **gituhb:** https://github.com/tearzday

## About US

Commercial experience of 3 years. I worked as an HTML-verstalker in campaigns that deal with advertising. My duties included development of sites with products for advertising, as well as development of internal systems, various technical support of the site and similar related things. At this stage I want to work in a team connected more with the development, get experience from colleagues, learn new things, well, and of course be useful and proud of what has turned out to create.

## Technology Stack

1. **Basic technologies:**
- HTML
- CSS/SCSS
- JavaScript

2. **Framework**
- Vue 3
- Vuex

3. **Other**
- GIT
- Node JS
- axios
- Knowledge of OOP and functional programming
- Knowledge of SPA
- Various algorithms (bubble sorting, linear search, etc.)

## Code Example
I have 6 kyu in CodeWars

**Description**
Create a function that will trim a string (the first argument given) if it is longer than the requested maximum string length (the second argument given). The result should also end with "..."

These dots at the end also add to the string length.

For example, trim("Creating kata is fun", 14) should return "Creating ka..."

If the string is smaller or equal than the maximum string length, then simply return the string with no trimming or dots required.

e.g. trim("Code Wars is pretty rad", 50) should return "Code Wars is pretty rad"

If the requested string length is smaller than or equal to 3 characters, then the length of the dots is not added to the string length.

e.g. trim("He", 1) should return "H...", because 1 <= 3

Requested maximum length will be greater than 0. Input string will not be empty.

**Result**
`const trim = (str, size) => (str.length > size && size > 3)?str.slice(0 , size - 3) + '...':(str.length <= size)?str:str.slice(0 , size) + '...'`