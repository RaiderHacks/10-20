## The html
test change

### `<html>`, `<head>` & `<body>` elements
First we are going to start off with our html document. This tells the browser where to start reading html, although it will still read anything you put inside of a file with a .html extention it's best practice to do this 
```html
<html>
</html>
```

Then we are going to add a `<head>` and a `body` tag within our html tags. 
Elements within the `<head>` tag are not rendered to the user. The `<head>` tag is where we are going to link our css and javascript files so we still need it.  wElements within the `<body>` tag **are** rendered to the user


```html
<html>
    <head>
        <!-- Links and stuff not rendered to the user -->
    </head>
        <body>
            <!-- Where our content will be rendered to the user -->
        </body>

</html>
```




Add a `<div>` tag with the class `container` within the `<body>` body tags.

```html
    <body>
        <div class="container">
    </body>
```

![image-20201017185647166](notes.assets/image-20201017185647166.png)
- All HTML elements can have attributes
    - The href attribute of `<a>` specifies the URL of the page the link goes to
    - The src attribute of `<img>` specifies the path to the image to be displayed
    - The width and height attributes of `<img>` provide size information for images
    - The alt attribute of `<img>` provides an alternate text for an image
    - The style attribute is used to add styles to an element, such as color, font, size, and more
    - The lang attribute of the `<html>` tag declares the language of the Web page
    - The title attribute defines some extra information about an element