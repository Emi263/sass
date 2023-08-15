## TIPS ##

CSS TIPS
1. [CSS concepts](https://web.dev/learn/css/)
2. [CSS responsive](https://web.dev/learn/design/)
3. Learn flexbox [here](https://flexbox.tech/)
4. Free resources: 
    [Freecodecamp tutorial](https://www.youtube.com/watch?v=OXGznpKZ_sA&ab_channel=freeCodeCamp.org) \
   [HTML/CSS project](https://youtu.be/p0bGHP-PXD4)


**SASS TIPS**

**1. Sass oficial documentation**
 Read Sass documenation at official [documentation](https://sass.com)
**2. Variables** 
  Sass allows you to use variables to store and reuse values throughout your stylesheets. 
  Declare variables using the $ symbol and take advantage of their flexibility and convenience.

  ```
  $primary-color: #3498db;

  .button {
    background-color: $primary-color;
    color: white;
  }
  ```
    

**3. Nesting** 

  Nesting in Sass helps organize your styles by nesting selectors within one another. 
  This improves readability and reduces repetition. However, avoid excessive nesting to prevent generating overly specific CSS rules.

  ```.navbar {
  background-color: #333;

  ul {
    list-style: none;
    padding: 0;

    li {
      display: inline-block;
      margin: 0 10px;
    }
  }
}
```

**4. @use, @forward**

  The @use and @forward rules in Sass provide a modular approach to importing and sharing styles between files. 
  Understand how these rules work to structure your Sass projects efficiently.

**5. @function ,@mixin, @extend, @each**

Learn about key Sass features like @function, @mixin, @extend, and @each. These features enable you to create reusable code snippets, manage styles more effectively, and maintain a consistent design language.

**6. BEM** 
  BEM is a naming convention for CSS classes that promotes a consistent and maintainable codebase. Familiarize yourself with BEM principles to write clean and structured styles.

```
  <div class="block">
   <div class="block__element"></div>
  </div>
```
7. Sass resource : [Sass tutorial](https://youtu.be/_a5j7KoflTs) 
