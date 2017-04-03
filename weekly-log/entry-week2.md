# Entry 2
## Installing SASS
Throughout this week, I have used code academy to help me intall SASS into my directory. 
I installed SASS into my workspace by, typing in my terminal `gem install sass`. 
Then I typed `sass -v`, My terminal returned `Sass 3.4.23 (Selective Steve)`. (if
this does not return, this means that SASS is not installed in your workspace terminal)

After, I was instructed to create a file `touch input.scss` (This is basically where you type in your code).


Then, I typed in my terminal `sass input.scss output.css`. (output.css = CSS file) (input.scss = SASS file)
By typing this in your terminal, the CSS is being updated with any changes you've made in your SCSS file.



## Why SCSS ?
SCSS is a special type of file for SASS, a program written in Ruby that assembles CSS style sheets for a browser. SASS adds lots of additional functionality to CSS like variables,
nesting and more which can make writing CSS easier and faster. Files are processed by the server running a web app to output a traditional CSS that your browser can understand.


Below there is an example of SCSS code:
```
.banner {
  font-family: 'Pacifico', cursive;
  height: 400px;
  background-image: url("lemonade.jpg");
   border : {
    top: $standard-border;
    bottom: $standard-border;
}
  .slogan {
  position: absolute;
  border: $standard-border;
  top: 200px;
  left: 25%;
  width: 50%;
  height: 200px;
  text-align: center;
    
background-color: $translucent-white;
    span {
  font-size: 24px;
  line-height: 200px;
}
   
}

  
}

```
Below there is an example CSS code:
```
.banner {
  font-family: 'Pacifico', cursive;
  height: 400px;
  background-image: url("lemonade.jpg");
  border-top: 4px solid black;
  border-bottom: 4px solid black;
}

.banner .slogan {
  position: absolute;
  border: 4px solid black;
  top: 200px;
  left: 25%;
  width: 50%;
  height: 200px;
  text-align: center;
  background-color: rgba(255, 255, 255, 0.3);
}

.banner .slogan span {
  font-size: 24px;
  line-height: 200px;
}

```

## Take-Aways
 One take away I have taken is that you should, carefully type in your terminal because I had missed one letter when typing in `sass input.scss output.css` which did not make one file. Go back and check for typing errors.
 
 Another take away is, working together is one of the things that helped me install SASS, "Two heads are better than one".
 
 My last take away is, playing around with your code so that you can be more creative with what you want as your final result. 


