---
notes: |
  After a variable has been declared, you can read its value by using its name further down your program:

  ```js
  let color = 'purple';

  // ...other code

  console.log(color);
  // => prints "purple" to your console
  ```

  Also, after a variable has been declared for the first time, you can update its value anytime further down in your code as follows

  ```js
  let color = 'purple';

  // ...other code

  color = 'blue';
  ```

  When **updating** an **already declared** variable, you **must not** use the variable keyword. The variable keyword is only used when you declare a new variable for the first time.

  Besides that, we also see that each code instruction - a so-called _statement_ - ends with a semi-colon `;`. It acts as like a colon after a phrase indicating to the browser that a full code instruction ends right there.

  **Note** In the examples above we're assigning a word, or a so-called _string_, to our variable `color`. A string describes a number of characters, either letters, numbers or special characters, which are _stringed_ together. A string always needs to be written in quotation marks - you are free to choose either single quotes ' or double quotes ".
---

#### working with variables

```js
let color = 'purple';

// ...other code

console.log(color);
// => prints "purple" to your console
```

```js
let color = 'purple';

// ...other code

color = 'blue';
```
