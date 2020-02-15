# HTML

## Introduction and structure of HTML

People access the web on their own devices (computers,phones, tablets etc...) using web browsers that then send a request to web servers across the internet that host the site itself.

Websites are sent over the web as HTML, CSS and Javascript, and the browser itself interprets the code to create the webpage we see.

When you type a site name, the computer contacts network of servers called domain name system (DNS) they give your browser the IP address associated with the requested domain.

Using of headings and subheadings in any documentary reflects the hierarchy of information.

- HTML Describes the structure of the page, it is defined by elements that are made up of two tags; an opening tag and a closing tag, and attributes tell us more about a tag, an attribute has two parts; a name and a value like src="something.html", the name is src and something.html is the value, the name of the attribute should be in **lowercase**, although HTML5 allows you to use uppercase attribute names,but its not recommended.

- Most of the attributes can be used on certain elements, althought some can appear on any element (like the lang attribute).

1- <head> element contains information about the page and it wont be shown on the page itself, you will usually find <title> element here.
2- <body> element everything inside this element is shown inside the main browser
3- <title> element they are shown at the top of the browser or on the tab for that page.

You need text editor to create web pages, that can be normal text editor like notepad (not recommended) or an IDE (integrated development environment) that got a special set of tools that help the programming process (like VS Code).

*   If you are working on **content management system** and you need to control that content, you will need special admin section that will help you control it by giving you special tools for it that will allow you to edit parts of the webpage rather than the entire page, so you will rarely see (html,head or body elements).

Most of the time they use the same template for different pages on the website, that will make it easier to change the content of one page rather than the content of every page seperately, they use text editors to edit the HTML code to your text.

## Looking at how other sites are built
You can always check the source code of a website (check the HTML file) by clicking "view source" 

# Chapter 9: Extra Markup

Because of the different versions of HTML, each web page should begin with **DOCTYPE** declaration to tell a browser which version of html the page is using (browsers usually display the page even if its not included), it can also help the browser render a page correctly.

* To add a comment, u should add an exclamation mark and two dashes, then end with 2 dashes, like <!-- -->, its a good idea to add comments to your code.

* The **ID** Attribute, it can be used only **ONCE**, every element can carry the ID attribute, its used to identify that element uniquely, its value should start with a letter or an underscore (Not a number or any other character), its also important to not use the same value on two different elements on the same page, it helps a lot with CSS, its known as a **Global attribute** because it can be used on any element.

* The **class** attribute, same as above but for one or more elements, except they can share the same value unlike ID.

* Block Elements: they will always start a new line in the browser window, examples of block elements: <h1>, <p>, <ul>, and <li>.

* Inline Elements: they continue on the same line as their counterpart element, ex: <a>, <b>, <em>, and <img>.

### Grouping text and elements in a block
*  div element: it allows you to group a set of elements together in one block-level box, In a browser, the contents of the <div> element will start on a new line, but other than this it will make no difference to the presentation of the page, using ID or class attribute on div element means that you can style it with CSS.

* The <span> element is like an inline equivalent of the div element, its mostly used with class or id attribute to style a specific portion with CSS.

* The IFRAME element <iframe> is a like a little window into another website, it can be used to embed google maps or any other site locally or on the web, u need width, height and src attributes to define the borders and the source of the site, it can contain the scrolling element but it wont be supported in html5, same as frameborder.

### Meta element lives inside the head element and it contains data about the webpage, its not visible to users.

Meta element is an empty element so it doesnt have a closing tag, it uses attributes to carry information, for example they can be used by name="something" or http-equiv="something"

Most common attributes are name and content attributes which tend to be used together.

* Robots meta indicates whether search engines should add the page to their results or not,a value of noindex can be used if it shouldnt be added, a value of nofollow can be used if search engines should add this page in their results but not any pages that it link to.

* Pragma prevents a browser from caching the page, its used after http-equiv.

* expires attribute option can be used when a page cache should expire and no longer be casched.

### Escape Characters can be used to include special characters that are reserved by the HTML code like the left and right anagled brackets.

so if you want to type one of those special characters you must use one of the escape codes, like &lt that is left angled bracket.

# HTML5 Layout

HTML5 introduced new elements that allows you to divide up parts of the page, and they are named to indicate their purpose.

Main parts of the new HTML5 code is: 

> <nav>
it contains major navigational blocks on the site

> <article>
It's a container to put text in, like a paragraph.

> <div>
its still important to use this to group together related elements.

> <footer>
usually contains info like copyright and trademarks

> <hgroups> 
they are headers

* We can help older browsers understand HTML5 code even thought they treat it like an inline element, you need to use a simple javascript known as html5shiv or html5shim, this does not work on IE8 or earlier, except if you have extra javascript, you dont need to understand javascript to use it, just place it inside a conditional comment which checks if the browser version is less than IE9, but it requires javascript to be enabled.

# Chapter 18: Process and Design

* A website should be designed with one question in mind, who is it for? if its for an individual, then you should ask aaquestions about your target audience like: 
1- What is their age range?

2- Which countries your visitors live in?

3- What is the average income for them?

and many many more questions that help you define your target demographic, and if its a company then ask questions like how big is their company? what is the company's budget?

* Site maps lets you plan website structure

* Wireframe is a sketch that organizes where information on each page goes.

* Differentiate between information using size, color and style, also you can use grouping and similarity to help simplify the information you present.

# JavaScript: Introduction & CH1: ABC of Programming

You need to know the vocabulary and structure of sentences in JS just like any new language you learn.

You can access and modify the content of the HTML webpage using javascript, program rules and instructions for the browser to follow and react to the events of the browser or the user.

jQuery helps with inconsistencies among different browsers.

* Scripts are set of instructions that your computer follows step by step.
Always start with a big picture and a plan on how to design your JS, first part of writing a script is stating your goal and the tasks that are needed to complete them, and then start coding each step.

Scripts might use only a subset of all the instructions.

* In computer programming, each physical thing in the world can be represented as an **object** (like the car and hotels in the book example), each object can have its own properties, events and methods.

* Properties : like the color of the car and engine etc...

Each property has a name and a value.

* Events: is the computer's way of sticking up its hand to say, "Hey, this just happened!", its a part of the script to activate a specific portion of the script itself.

* Methods: its like a set of instructions that are already defined, you just need to give it variables.

Javascript doesnt change the source code of HTML, it just shows a link to the HTML file.

















