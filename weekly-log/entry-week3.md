# Entry 3
## Trying out Variables
Throughout this week, I decided that I wanted to focus more on Variables. I googled "SASS Variables" and I clicked on a link. 
I learned that variables are a way to store information where I can reuse throughout my SCSS file.

Below is an example of SCSS Syntax: 

```css
$font-stack:    Helvetica, sans-serif;
$primary-color: #333;

body {
  font: 100% $font-stack;
  color: $primary-color;
}
```

Below is an example of CSS Syntax:


```css
body {
  font: 100% Helvetica, sans-serif;
  color: #333;
}
```

As you can see, SCSS uses a variable `font-stack` that has the value of "Helvetica, sans-serif". Instead of typing the whole value, you create a variable that equals that value. 
In CSS you do not use variables. Therefore, you have to type in the type of font or color, you want it to be. This may lead you to be typing that value 50 times, which is a lot of time consuming. 
This is why, SCSS is faster, easier and a neat way to code. This was my ah-ha moment about how to use a variable so, I began to try it in c9.

Here's an example of my `input.scss` below:



```css
$font: verdana;
$color:  #ff1aff;
$font-size: 160%; 

h1 {
  font: 100% $font;
  color: $color;
  font-size: $font-size;
}

h3 { 

  font: 100% $font;
  color: $color;
  font-size: $font-size;
  
}

```
My code above, shows my variables `$font`, which is set equal to the font "verdana", `$color`, is set equal to ` #ff1aff`, `$font-size` is set equal to `160%`.



Now, I'll show you my CSS code below:




```css

h1 {
  font: 100% verdana;
  color: #ff1aff;
  font-size: 160%; }

h3 {
  font: 100% verdana;
  color: #ff1aff;
  font-size: 160%; }

```
In my own words, I say that, my code in my SCSS file is being translated into CSS on the CSS file. Therefore, you see the VALUES of the variables in the CSS file.








## Take-Aways
 * Tinkering 
