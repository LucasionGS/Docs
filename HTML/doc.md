# HTML Documentation

## **\<!-- Comment -->**
```html
<!-- This is a comment -->
```
You'll see this tag quite a lot in this documentation, as it's used inside of the code.
writing ``<!-- text here -->`` is writing a comment in HTML, and will not be displayed in the document.  
Comments are used like placeholder texts just for the developer, small foot notes, inline documentation, etc...
The differnece between a normal tag and a comment tag when writing it, is that the normal tags are just ``<>`` with text inside like ``<body>``, but the comment has ``<!--`` on the start and ``-->`` on the end

## **\<html> tag**
```html
<html>
  <!-- Everything else -->
</html>
```
The ``html`` tag is the main tag of your HTML document. It should be used as the very first tag of your document. The starting tag should be the first tag in your code and the ending tag should be the last in your code.

## **\<body> tag**
```html
<body>
  <!-- Your main content of the page -->
</body>
```
The ``body`` tag is where your main content of your page is. Practically everything graphical you'll make should be within ``body``.

## **\<div> tag**
```html
<div>
  <!-- Content -->
</div>
```
The ``div`` tag is mainly used for containing other tags. Think of a div as ``body`` within the ``body``, and can be used to make sections of content.

Example of use: (the ``style`` attribute will be explained later)
```html
<html>
  <body style="margin: 0; padding: 0;">
    <div style="width: 25%; height: 100vh; background-color: black; float:left;">
      <p style="color: white">This is a sidebar</p>
      <p style="color: white">Maybe something like a content list</p>
    </div>

    <div style="width: 75%; height: 100vh; background-color: white; float:left;">
      <p>This can be other content</p>
    </div>
  </body>
</html>
```
![example](https://lucasion.xyz/f/21.49.11-02.12.19.png)

## **\<p> tag**
```html
<p>This is text</p>
```
The ``p`` tag standards for *paragraph* and is exactly that, a paragraph. It is used to write text inside and is the standard tag to write text inside of. Each ``p`` tag uses its own line. ``p`` tag do not support just pressing Enter to get a new line by default (this can be changed with styling). Instead, you must use ``<br>`` to make a new line. ``p`` tags automatically has a margin and padding on it by default, which means it will look very spacious around it. It can be removed with styling.

Example of use:
```html
<html>
  <body>
    <p>This is a regular text paragraph.</p>
    <p>
      This is a text paragraph
      and a new line that only shows in the code.
    </p>
    <p>This is also a text paragraph<br>and this one does show it on a new line, but same p tag.</p>
  </body>
</html>
```
![example](https://lucasion.xyz/f/22.15.13-02.12.19.png)