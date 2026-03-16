# HTML, CSS, JS
HTML = Structure/layout.
CSS = Style.
JS = Logic.

# HTML
Hyper Text Markup Language

HTML is the code that is used to structure a web page and its content.

The component used to design the sturcture of websites are called HTML tags.

## First HTML File
index.html

It is the default name for a website's homepage.

## HTML Tag
A container for some content or other HTML tags.

## Basic HTML Page
< !DOCTYPE html > = tells browser you are using HTML5<br>
< html>< /html> = root of an html document<br>
< head>< /head> = container for metadata.<br>
< title></ title> = page title
< body></ body> = contains all data rendered by the browser
< p></ p> = paragraph tag

## Quick Points
HTML tag is parent of head & body tag.

Most of html elements have opening & closing tags with content in between.

Some tags have no content in between, eg - < br>.

We can use inspect element/view page source to edit html.

## Comments in HTML
This is part of code that should not be parsed.

<! --This is an HTML Comment-->

## HTML is NOT case sensitive
< html> = < HTML>

## Basic HTML Tags
### HTML Attributes
Attributes are used to add more information to the tag.

< html lang="en">

## Heading Tag
Used to display headings in HTML.

h1 (most important)<br>
h2<br>
h3<br>
h4<br>
h5<br>
h6 (Least important)

## Paragraph Tag
Used to add paragraphs in HTML

< p>This is a sample paragraph</ p>

## Anchor Tag
Used to add links to your page

< a href="https://google.com"> Google </ a>

< a> href="https:google.com" target="_main"> Google </ a> (for new tab)

< a> href="https:google.com"><img src="link"> </ a> (clickable picture)

## Image Tag
Used to add images to your page

< img src="/image.png" alt="Random Image">

## Br Tag
Used to add next line (line breaks) to your page

< br>

## Bold, Italic & Underline Tags
Used to highlight text in your page

< b> Bold </ b>

< i> Italic </ i>

< u> Underline </ u>

## Big & Small Tags
Used to display big & small text on your page.

< big> Big </ big>

< small> Small </ small>

## Hr Tag
Used to display a horizontal ruler, used to separate content.

< hr>

## Subscript & Superscript Tag
Used to display a horixontal ruler, used to seprate content.

< sub> subscript </ sub>

< sup> superscript </ sup>

## Pre Tag
Used to display text as it is (without ingoring spaces & next line).

< pre> This
is a sample
text.
</ pre>

## Page Layout Techniques
Using Semantic tags for layout.
Using the right Tags.

< header><br>
< main><br>
< footer>

## Inside Main Tag
1. Section Tag = For a section on your page

< section>

2. Article Tag = for an article on your page

< article>

3. Aside Tag = for content aside main content(ads)

< aside>

## Div Tag
Div is a container used for other HTML elements.

Block Element (takes full width)

## Span Tag
Span is also a container used for other HTML elements.

Inline Element (takes width as per size)

## List in HTML
List are used to represent real life list data.

1. unordered.

< ul> </ ul>

2. ordered.

< ol> </ ol>

## Tables in HTML
Tables are used to represent real life table data.

< tr> used to display table row

< td> used to display table data

< th> used to display table header

## Caption in Table
< caption> Student Data </ caption>

## thead & tbody in Tables
< thead> to wrap table head

< tbody> to wrap table body

## Form in HTML
Forms are used to collect data from the user. Eg - sign up/login/helop requests/contact me.

< form>

form content

</ form>

## Action in Form
Action attribute is used to define what action needs to be performed when a form is submitted.

< form action="/action.php">

## Form Element: Input

< input type="text" placeholder="Enter Name">

## Label
< label for="id1">

    <input type="radio" value ="class X" name="class" id="id1">

</ label>

## Class & Id
< div id="id1" class="group1">

</ div>

< div id="id2"> class="group1">
</ div>

## Checkbox
< label for="id1">

    <input type ="checkbox" value="class X" name="class" id="id1">

</ lable>

< label for="id2">

    <input type="checkbox" value="class X" name="class" id="id2">

</ label>

## Select
< select name="city" id="city">

    <option. value="Delhi"> Delhi </option>
    <option. value="Mumbai"> Delhi </option>
    <option. value="Banglore"> Delhi </option>

</ select>

## iframe Tag
website inside website

< iframe src="link">

## Video Tag
< video src="link"> My video </ video>

Attributes
- controls
- height
- width
- loop
- autoplay