# Skills communicate using markdown


### Adding an image
-------------------
To add an image :

`![<descriptive-text>](<url>)`

Include descriptive text in the square brackets.This text is read aloud for people using screen readers. It's also shown at times when your image doesn't display, such as when there's a poor connection
> Exmple : `![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)`

The Output:

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)



### Adding a code 
-----------------
In addition to code blocks, some code blocks should be rendered differently depending on the language.



#### Command line

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```


#### Javascript

``` js
var myVar = "Hello, world!";
```

#### Html

``` HTML
<div class="row">
  <div class="col-md-6 col-md-offset-3">
    <h1>Hello World</h1>
  </div>
</div>
```

#### Python

``` python
a, b = 0, 1
while b < 10:
    print(b)
    a, b = a, a + b
```


### Adding a list
-----------------

- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
