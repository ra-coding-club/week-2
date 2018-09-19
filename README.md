[Home](https://ra-coding-club.github.io/coding-club) | [Week 1](https://ra-coding-club.github.io/week-1/) | **[Week 2](https://ra-coding-club.github.io/week-2/)**

# Do You Have Style?

**C**ascading **S**tyle **S**heets (CSS) are used to... style HTML.

There are three ways to use CSS with your webpage.

## In-line Styling

Typical use of inline CSS:

```` HTML
<!DOCTYPE html>
<html>
  <head></head>
  <body>
    <h1 style="color:red;">This heading will be red.</h1>
  </body>
</html>
````

## Internal Styling

Typical use of internal CSS:

```` HTML
<!DOCTYPE html>
<html>
  <head>
    <style>
      h1 {color: red;}
    </style>
  </head>
  <body>
    <h1>This heading will be red.</h1>
  </body>
</html>
````

## External Styling

Typical use of external CSS:

```` HTML
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>This heading will be red.</h1>
  </body>
</html>
````

styles.css:

```` CSS
h1 {
color: red;
}
````

# Google is Your Friend!

Use the internet to your advantage - no coder can memorize every rule in any programming or markup language. Therefore many reference sites have been created just to help *you*, the awesome coder, out:

* [Stack Overflow](https://stackoverflow.com/)
* [Mozilla Developer Network](https://developer.mozilla.org/en-US/)
* [W3 Schools](https://www.w3schools.com/)

**Copyright &copy; 2018 Riyaad Azad. Free to copy and distribute as per the [official license on GitHub](https://github.com/ra-coding-club/coding-club/blob/master/LICENSE). All other rights reserved.** 
