## Vitalina Ustalkova
**Junior Frontend Developer**
### Contact information:

- **Phone:** +79043992883
- **E-mail:** vita.ustalkova@bk.ru
- **Telegram:** @ustalkovaV

### Briefly About Myself:

### Skills and Proficiency:

* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code
* Adobe Photoshop, Illustrator

### Code example:
Homogenous arrays KATA from **CODEWARS**:
Given a two-dimensional array, return a new array which carries over only those arrays from the original, which were not empty and whose items are all of the same type (i.e. homogenous). For simplicity, the arrays inside the array will only contain characters and integers.

```javascript
function filterHomogenous(arrays) {
  let res;
  const isHomogenous = (array) => { for (let i = 0; i < array.length; i++) {
    if(typeof(array[0]) === typeof(array[i])){
      res = true;}
      else return false;
    }
    return res;}
  let result = arrays.filter((el) => { return isHomogenous(el)})
  
  let homogenous = result.filter((el) => el.length > 0)
  return homogenous;
}
```

### Courses:
RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

### Languages:
- **English** - Pre-Intermediate (according to the online test at [Lingualeo](https://lingualeo.com/ru/quiz/welcome)) 
- **Russian** - Native