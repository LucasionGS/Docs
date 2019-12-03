# CSS General
## **/\* Comment \*/**
```css
/* This is a comment */
```
Writing comments in CSS can only be done by surrounding text by ``/* */``. Anything inside of comment "brackets" like those, won't be used by the CSS code, and ignored.

# CSS Syntax
When writing basic CSS, you first need a ``selector``.  
A ``selector``is the reference to an HTML element. ``Selectors`` can  for instance, look like some of these:
```css
div{
  /* This selects every div element in the document */
}

div.container{
  /* This selects every div element with a Class called "container" */
  /* Class references are separated by a "." */
}

p.content{
  /* This selects every p element with a Class called "content" */
}

p.content.another{
  /* This selects every p element with BOTH of the classes "content" AND "another" */
}

.content{
  /* This selects every element that has the class called "content" */
  /* You can use both classes and IDs without specifying an element */
}

img#mypicture{
  /* This selects the img element with the ID "mypicture" */
  /* IDs are selected with # after the element's tag */
}

div#mydiv.content{
  /* This selects the div element with the ID "mydiv" AND the Class called "content" */
  /* IDs are selected with # after the element's tag */
}
```