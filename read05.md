# Designing web pages using CSS

CSS allows you to change how the content of an HTML file appears,it's used for styling the web page structure that you created in HTML.

You can control the width, margins, padding, style, font and many more properties of how it looks.

You can style your HTML in 3 ways

1- Inline ***Not Recommended***.
its like <h1>style.... </h1>

2- Embedded ***Not Recommended***.
its like <style>
    you put ur code here {

    }
    and close the tag with </style>
3- External Sheet ***Best way to do it***.

Benefits for using the external style sheets:
Can be used for multiple html pages, which also means the user has to download the css file only once and that means faster load times for the end user, also if you want to make a change to all of your pages, then all you have to do is edit a single css file for it to take effect on all the pages.

When you use an external CSS sheet, you must link it to your HTML file in the head part using 
> <link rel="stylesheet" href="">

There are different types of selectors:
> * {} applies to all elements
> h1, h2 .... type selector
> .note --> class selector (can be used multiple times)
> #note --> ID selector (can be used once only)

## Color in CSS
There are many ways to specify a color;

1- Color names
2- Hex codes: six digit codes that represent amount of blue red and green in a color preceded by a hash, like #ee3e80 
3- RGB values; they range from 0 to 255 of each red green or blue like: rgb(100,50,90);

**You can add a comment in css by using " /* .. */ "**

Color commands in CSS:
* color: white; (text color)
* background-color 

Using low contrast makes it hard to read text, using high contrast makes the text easier to read but not for long text, the best choice is medium contrast.



