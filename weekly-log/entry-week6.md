# Entry 6
### Extend.
Well, as I have been learning Sass in Code Academy I've came across to ```css @Extend```. 

Look below for an example:

```css
.lemonade {
  border: 1px yellow;
  background-color: #fdd;
}
.strawberry {
  @extend .lemonade;
  border-color: pink;
}

```

Extend is basically having all the code in a memory card that you have in ```css.lemonade```. By typing ```css @extend .lemonade``` 

in a different section of your entire code, will have the same code from```css .lemonade```.


I think using ```csss @extend     ``` is an easy way to save time while coding because let's say you have a bunch 
of code that you want to reuse in a different section, 
Yes, you are probably thinking just copy and paste, right? Copy and pasting is a good idea but, 
having too much code, makes it harder to solve or find errors and/or bugs. We dont want that.
Therefore, using ```css @extend``` can save you time, and a neater way to code.

<br>
### The Symbol.
<br>
Sass allows a special type of selector called a placeholder, which behaves just like a class or id selector. Instead of # or . , Sass uses the % sign.
Below there is an example:
```css
a%drink {
    font-size: 2em;
    background-color: $lemon-yellow;
 }
 .lemonade {
  @extend %drink;
  //more rules
 }
would translate to 
 a.lemonade {
    font-size: 2em;
    background-color: $lemon-yellow;
 }

.lemonade {
  //more rules
}
Below there is an example:
```

```css
a%drink {
    font-size: 2em;
    background-color: $lemon-yellow;
 }

 .lemonade {
  @extend %drink;
  //more rules
 }
would translate to 
 a.lemonade {
    font-size: 2em;
    background-color: $lemon-yellow;
 }

.lemonade {
  //more rules
}

```


### Choosing a Topic.



<img src="../face.png"/>
 

After not having a clue of what my project is going to be about, to having a little tiny ideas, to deciding what my topic is going to be about but I don't know what exactly my template or design is going to look like. 
Mhmmmmm.... I've decide my topic is going to be about Dance and giving the viewer information about dance. 

### Take-A-Ways!

1.) Asking peers questions about what you're learning, is a huge help and support.
<Br>
2.) PATIENCE, having some patience is something that we should have with ourselves.
<br>
3.) Re-reading and looking back to previous websites/readings to have a clearer understanding.



 