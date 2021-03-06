#The `background-image` Property Explained

The `background-image` property allows you to set one or multiple background images for any given element. This property can apply 2 different types of images: regular images (e.g. PNG,SVG,GIF,JPG) or gradients, to the background of an element.

The background of an element is the total size of the element, including any padding and border, but doesn't include the margin.

A background-image is placed at the top-left corner of an element, by default, and is repeated both horizontally and vertically. You are still able to add content in front of the image (i.e. text and other elements). 

##Syntax
Depending on your intent, the syntax will usually look like one of the following:

```

background-image: url("http://www.example.com/bgi.jpg")

background-image: inherit;

background-image: initial;

background-image: none;

```


###Values
| Value  | Description  |
|---|---|
|url('URL')|URL to image. To specify more than 1 image, separate the URLs with comma|
|initial|Sets property to its default value|
|inherit|Inherits property form parent element|
|none|No background image is displayed. (Default)|


##Example 1

The basic `background-image` css property

```
body {
    background-image: url("img.jpg"), url("img2.jpg");
    background-color: #cccccc;
}
```

##Example 2
By default the background image repeats
![Imgur](http://i.imgur.com/vxPV1Lg.png =1000x)

##Example 3
Using a gradient as a background image
![Imgur](http://i.imgur.com/8OvQhGD.png =1000x)


##Example 4
Combining background images and gradients
![Imgur](http://i.imgur.com/ovNk1wk.png =1000x)


