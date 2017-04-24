# Entry 4
## Trying out Mixins


In Sass, the "&" character is used to represent where a parent selector should be inserted. It also helps write psuedo classes in a much less repetitive way.


Like the example below:

```css
.notecard{ 
  &:hover{
      @include transform (rotatey(-180deg));  
    }
  }

```


The code below is an example of mixin:


```css

@mixin backface-visibility {
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  -ms-backface-visibility: hidden;
  -o-backface-visibility: hidden;
}
```
Throughout week 4, I have used code academy to help me learn Mixins. A mixin lets you make groups of CSS declarations that you want to reuse throughout your site. 
You can even pass in values to make your mixin more flexible. 



I tried it out, creating a note card, that has text where, when it is hovered the note care rotates in the y-axis. This makes the text be reflective, makes the text look really cool on the the note card.

```css
.notecard {
  width: 300px;
  height: 180px;
  border: 1px solid black;
  display: inline-block;
  margin: 20px;
  font-family: 	Courier New, Courier New;
  box-shadow: 1px 1px 2px 2px rgba(0,0,0,.2);
  &:hover{
  @include transform (rotatey(-180deg)); 
``` 



# Take Aways
1.) Ask questions!! if you have to your peers because they are a great resource!! 

2.) Tinkering and searching for definitions if you do not understand a word or specific code.

3.) Be able to play around with the code, to get familiar with it.


