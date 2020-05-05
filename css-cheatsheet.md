## Cascading Style Sheets (CSS)

CSS is one of the foundations for the Webpage Development. It is used for describing the presentation of a document written in a markup language like HTML(Hypertext Markup Language)

### Overview

You will often want something other than the choice the browser has made. This can be done by simply choosing the HTML element that you want to change, and using a CSS rule to change the way it looks.

### Examples

Applying external CSS

```
1 | <link rel="stylesheet" href="styles.css">
```

Applying internal CSS

```
1 |    <head>
2 |        <title>Internal CSS</title>
3 |     <style>
4 |         .main {
5 |            text-align:center;
6 |         }
7 |         .geeks {
8 |             font-style:bold;
9 |             font-size:20px;
10|          }
11|     </style>
12| </head>

```

Applying inline CSS

```
    <body>
        <p style = "color:#009900; font-size:50px;
                font-style:italic; text-align:center;">
            GeeksForGeeks
        </p>
    </body>
```

### links

- https://en.wikipedia.org/wiki/Cascading_Style_Sheets
- https://www.w3schools.com/css/css_intro.asp
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model

> THINGS AIN'T ALWAYS #000000AA ain't always #000000 and #ffffff
