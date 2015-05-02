## CSS Guide

#### Width
values: `pixel`, `percentage`, `auto`
```
width: 100%;
max-width: 500px;
min-width: 200px;
```

#### Height
values: `pixel`, `percentage`, `auto`
```
height: 100%;
max-height: 500px;
min-height: 200px;
```

#### Margin
the space between an element and the surrounding elements
values: `pixel`, `percentage`, `auto`
```
margin: [all sides];
margin: [top/bottom] [left/right];
margin: [top] [right] [bottom] [left];
```

#### Padding
the space inside an element
values: `pixel`, `percentage`, `auto`
```
padding: [all sides];
padding: [top/bottom] [left/right];
padding: [top] [right] [bottom] [left];
```

#### Display
display behavior of an element; most elements are default `block`
some are default `inline`: `img`, `a`, `span`, `em`, `strong`
values: `block`, `inline`, `inline-block`
```
display: [value];
```

#### Background
short hand first, with specific properties next:
```
background: [color] [image] [repeat] [position];
```
values: `color name`, `hex code`, `rgb`, `transparent`
```
background-color: #f7f7f7;
background-color: blue;
background-color: rgba(255,255,255);
```
a background image can be an absolute path:
```
background-image: url(http://website.com/image.png);
```
or a relative path:
```
background-image: url(../images/image.png);
```
should the background image repeat and how
values: `repeat`, `no-repeat`, `repeat-x`, `repeat-y`
```
background-repeat: no-repeat;
```
where should the background image be positioned
values: `top`, `bottom`, `left`, `right`, `center`, `pixel`, `percentage`
background-position: [x-axis] [y-axis];
background-position: left top;
background-position: 30% bottom;
background-position: center 40px;
```
what size should the background image be
values: `contain`, `cover`, `pixel`, `percentage`, `auto`
```
background-size: cover;
background-size: [width] [height];
background-size: 40px auto;
```

### Borders

#### Border
short hand:
```
border: [width] [style] [color];
border: 1px solid red;
```
how wide should the border be:
values: `pixel`, `percentage`
```
border-width: 10%;
border-width: 10px;
```
what style should the border have:
values: `solid`, `dotted`, `dashed`, `double`, `groove`, `ridge`, `inset`, `outset`
```
border-style: solid;
```
what color should the border be:
values: `color name`, `hex code`, `rgb`
```
border-color: #f7f7f7;
border-color: blue;
border-color: rgba(255,255,255);
```
you can also set a specific border:
```
border-top: 1px solid red;
border-right: 1px solid blue;
border-bottom: 1px solid green;
border-left: 1px solid yellow;
```

#### Border radius
makes rounded corners or circles
values: `pixel`, `percentage`
```
border-radius: [all corners];
border-radius: [top-left/bottom-right] [top-right/bottom-left];
border-radius: [top-left] [top-right] [bottom-right] [bottom-left];
```
you can also set a specific corner:
```
border-top-left-radius: 10px;
border-top-right-radius: 20px;
border-bottom-right-radius: 30px;
border-bottom-left-radius: 40px;
```

#### Box Shadow
drop shadow for an element
```
box-shadow: [inset] [x-offset] [y-offset] [blur] [color];
box-shadow: 10px 10px 5px red;
box-shadow: inset 10px 10px 0 #444;
```

#### Typography
set the font to use
this is a font stack. if the first in the list isn't available for the user, the next one in the list will be used and so on.
```
font-family: Helvetica, Arial, sans-serif;
```
specifiy the font size
values: `pixel`, `percentage`, `em`, `rem`
```
font-size: 16px;
```
specify the font weight
values: `normal`, `bold`, `number`
```
font-weight: normal;
font-weight: 400;
```
specify the line height (leading)
values: `number`, `pixel`, `percentage`
line-height: 1.4;
line-height: 18px;
```
color of the text
values: `color name`, `hex code`, `rgb`
```
color: blue;
color: #bebebe;
color: rgb(0,0,0);
```
alignment of the text
values: `left`, `right`, `center`, `justify`
```
text-align: left;
```
italicize text via style
values: `normal`, `italic`, `oblique`
```
font-style: italic;
```
decorate the text
values: `none`, `underline`, `overline`, `line-through`
```
text-decoration: underline;
```
transform the text
values: `none`, `uppercase`, `lowercase`, `capitalize`
```
text-transform: uppercase;
```
text shadow
```
text-shadow: [x-offset] [y-offset] [blur] [color];
text-shadow: 2px 2px 5px red;
```

#### Opacity
set the opacity as a decimal between 0 and 1
```
opacity: .4;
opacity: 1;
opacity: 0;
```

CSS Comments:
```
/* css comments look like this */
```

Further reference:
- [CSS reference - w3schools.com](http://www.w3schools.com/cssref/default.asp)
- [CSS tutorials - w3schools.com](http://www.w3schools.com/css/default.asp)
- [CSS tutorials - codecademy.com](http://www.codecademy.com/courses/css-coding-with-style/0/1)