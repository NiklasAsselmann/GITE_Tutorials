# Html and CSS

Created: Jun 23, 2020 5:47 PM

### What We Need To Start?

- A Web Browser, any one of the following browsers:
    - Google Chrome
    - Mozilla Firefox
    - Safari
    - Edge
- A Text Editor, any one of the following Text editors
    - Sublime Text
    - Atom.io
    - Visual Studio
    - Brackets
    - Notpad++(Windows)
    - TextMate(Mac)

## What is HTML ?

- **Hyper Text Markup Language**
- **Not** Programming Language
- Markup for creating Webpages / documents

### Creating an HTML file

- Does Not need a server
- File must end with .html extension
- Runs in web browser

**Hint:** Index.html is the *root/ home* page of a website for example *Http://www.example.com l*oads the index.html file. While  *[Http://www.example.com/about.html](http://www.example.com/about.html)  l*oads the about.html file.

**Steps to create an html file**
- make a new text file
- change its extension to __.html__
- open it using text editor
- add the html syntax.

<p align="center"><img src="https://i.imgur.com/AU9JUdS.gif" height="500" alt="alt text" title="headings demo"></p>

**Tag Syntax**

```html
<tagename>content</tagname>
<h1>About Us</h1>
<p>This is a paragraph</p>
<br/> (self closing)
<br>  (Fine in HTML5)
```

- Element names surrounded by angle brackets
- Normally come in pairs(start and end tag)
- End tag is usually the same but with forward slash
- Some tags close themselves

<p align="center"><img src="https://i.imgur.com/ieTqcVI.gif" height="500" alt="alt text" title="basics demo"></p>
<p align="center"><img src="https://i.imgur.com/IHl3e5y.gif" height="500" alt="alt text" title="basics demo"></p>

# HTML Elements

HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

The following example is a basic HTML Document In its simplest form, it contains four HTML elements (`<html>`, `<body>`, `<h1>` and `<p>`):

```html
<!DOCTYPE html>
<html>
		<head>
				<title>This is document title</title>
		</head>
		<body>
				<h1>This is a heading</h1>
				<p>Document content goes here.....</p>
				<p>Document content goes here.....</p>
		</body>
</html>
```

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph

# The <!DOCTYPE> Declaration

The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

# HTML Headings

HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading:

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```
<p align="center"><img src="https://i.imgur.com/gQChqlz.gif" height="500" alt="alt text" title="headings demo"></p>

# HTML Paragraphs

HTML paragraphs are defined with the `<p>` tag:

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
<p align="center"><img src="https://i.imgur.com/BTcJJGo.gif" height="500" alt="alt text" title="paragraphs demo"></p>

# Exercise :
create an Html page that looks the same like in the following example applying what you have learned Untill now.

<p align="center"><img src="https://www.dummies.com/wp-content/uploads/280295.image0.jpg" height="500" alt="alt text" title="exercise1"></p>

# HTML Links

HTML links are defined with the `<a>` tag, and the link's destination is specified in the `href` attribute.

```html
<a href="https://www.google.com">google</a>
```


**Hint:** Attributes are used to provide additional information about HTML elements.

# HTML Images

HTML images are defined with the `<img>` tag.

The source file (`src`), alternative text (`alt`), `width`, and `height` are provided as attributes:

```html
<img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" alt="google" width="104" height="142">

```

<p align="center"><img src="https://i.imgur.com/5IpzvW1.gif" height="500" alt="alt text" title="images demo"></p>

# HTML Attributes

- All HTML elements can have **attributes**
- Attributes provide **additional information** about elements
- Attributes are always specified in **the start tag**
- Attributes usually come in name/value pairs like: **name="value"**

# HTML Formatting Elements

Formatting elements were designed to display special types of text:

- `<b>` - Bold text
- `<strong>` - Important text
- `<i>` - Italic text
- `<em>` - Emphasized text
- `<mark>` - Marked text
- `<small>` - Smaller text
- `<del>` - Deleted text
- `<ins>` - Inserted text
- `<sub>` - Subscript text
- `<sup>` - Superscript text

# HTML `<b>` and `<strong>` Elements

The HTML `<b>` element defines bold text, without any extra importance.

```html
<b>This text is bold</b>
```

The HTML <strong> element defines text with strong importance. The content inside is typically displayed in bold.

```html
<strong>This text is important!</strong>
```

<p align="center"><img src="https://i.imgur.com/cPZazIh.gif" height="500" alt="alt text" title="bold demo"></p>

# HTML `<i>` and `<em>` Elements

The HTML `<i>` element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.

**Hint:** The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

```html
<i>This text is italic</i>
```

<p align="center"><img src="https://i.imgur.com/F9lYuo7.gif" height="500" alt="alt text" title="italic demo"></p>

The HTML `<em>` element defines emphasized text. The content inside is typically displayed in italic.

```html
<em>This text is emphasized</em>
```

**Hint:** A screen reader will pronounce the words in `<em>` with an emphasis, using verbal stress.

<p align="center"><img src="https://i.imgur.com/GdyMJIk.gif" height="500" alt="alt text" title="em demo"></p>

# HTML `<small>` Element

The HTML `<small>` element defines smaller text:

```html
<small>This is some smaller text.</small>
```
<p align="center"><img src="https://i.imgur.com/LJG8Dlt.gif" height="500" alt="alt text" title="small demo"></p>

# HTML `<del>` Element

The HTML `<del>` element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:

```html
<p>My favorite color is <del>blue</del> red.</p>
```
<p align="center"><img src="https://i.imgur.com/vO9EXnV.gif" height="500" alt="alt text" title="delete demo"></p>

## HTML Styles

The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

The HTML style attribute has the following syntax:

```html
<tagname style="property:value;">
```

# Background Color

The CSS `background-color` property defines the background color for an HTML element.

```html
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```

<p align="center"><img src="https://i.imgur.com/V27kcGG.gif" height="500" alt="alt text" title="styles demo"></p>

# Text Color

The CSS `color` property defines the text color for an HTML element:

```html
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```

<p align="center"><img src="https://i.imgur.com/B7oszzu.gif" height="500" alt="alt text" title="styles demo"></p>

# Fonts

The CSS `font-family` property defines the font to be used for an HTML element:

```html
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
```

# **Text Alignment**

The CSS `text-align` property defines the horizontal text alignment for an HTML element:

```html
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
```

<p align="center"><img src="https://i.imgur.com/RN7GVXV.gif" height="500" alt="alt text" title="styles demo"></p>

# Exercise :
create an Html page that looks the same like in the following example applying what you have learned Untill now.

<p align="center"><img src="https://i.imgur.com/y5jcJEz.png" height="500" alt="alt text" title="exercise 2"></p>


# LISTS

the lists have three types:

- ordered list `<ol>`: will automatically generate a number for each entry in the list.
- unordered list `<ul>`:  with simple bullet points instead of numbers.

```html
<h3> Fruits! </h3>

<ol>
	<li> Apple </li>
	<li> Carrot </li>
	<li> Orange </li>
	<li> Plum </li>
	<li> Watermelon </li>
</ol>

<h3> Dogs! </h3>

<ul>
	<li> Chow Chow </li>
	<li> Dachshund </li>
	<li> German Shepherd </li>
	<li> Pit Bull </li>
	<li> Whippet </li>
</ul>
```

### Fruits!

1. Apple
2. Carrot
3. Orange
4. Plum
5. Watermelon

### Dogs!

- Chow Chow
- Dachshund
- German Shepherd
- Pit Bull
- Whippet

## Tables

There are several layers to defining a table.

- `<table>` Defines the table start
- `<tr>` Table row
- `<th>` Table header for top and side cells (optional).
- `<td>` Actual table data, an individual cell.

```html
<table style="text-align:center;" width="200" border="1">
  <tr>
    <td></td>
	<th>A</th>
	<th>a</th>
  </tr>
  <tr>
  	<th>A</th>
    <td>AA</td>
    <td>Aa</td>
  </tr>
  <tr>
    <th>a</th>
    <td>Aa</td></td>
    <td >aa</td>
  </tr>
</table>
```

## **1.What is CSS?**

`Cascading Style Sheets (CSS)`is a stylesheet language used to describe the presentation of a document written in HTML or XML . CSS describes how elements should appear on screen, on paper, in speech, or on other media.

### **3 ways of using css**

- Inline: using a style= attribute for single HTML elements inside `<body>`

```html
<!DOCTYPE html>
<html>
	<body>
		<h1 style="color:blue;margin-left:30px;">This is a heading</h1>
		<p>This is a paragraph</p>
	</body>
</html>

```

- Internal: using a `<style>` element in the HTML `<head>` section

```html
 <!DOCTYPE html>
<html>
	<head>
		<style>    
		body {
		    background-color:Blue;
		}
		h1{
		   margin-left:30p
		}
		</style>    
	</head>

	<body>
		<h1>This is aheading</h1>
		<p>This is a paragraph</p>
	</body>
</html>

```

- External: using one or more external CSS files

In html file

```html
 <!DOCTYPE html>
<html>
	<head>
		<link rel="stylesheet" 	type="text/css" hrel="mystyle.css" >
	</head>
	<body>
		<h1>This is aheading</h1>
		<p>This is a paragraph</p>
	</body>
</html>

```

In mystyle.css file

```css
p {background-color:Blue;}
h1{margin-left:30p;}

```

## **2.Element in CSS**

### Element Selector

an *`element selector`* — this is a selector that directly matches an HTML element name. To target all paragraphs in the document you would use the selector `p`. To turn all paragraphs green you would use:

```css
p {
  color: green;
}
```

You can target multiple selectors at once, by separating the selectors with a comma. If I want all paragraphs and all list items to be green my rule looks like this:

```css
p, li {
    color: green;
}
```

### Adding class

In your HTML document, add a class attribute to the second list item. Your list will now look like this:

```html
<ul>
	<li>Item one</li>
	<li class="special">Item two</li>
	<li>Item <em>three</em></li>
</ul>
```

In your CSS you can target the class of `special` by creating a selector that starts with a full stop character. Add the following to your CSS file:

```css
.special {
  color: orange;
  font-weight: bold;
}
```

Save and refresh to see what the result is.

You can apply the class of `special` to any element on your page that you want to have the same look as this list item. For example, you might want the `<span>` in the paragraph to also be orange and bold. Try adding a `class` of `special` to it, then reload your page and see what happens.

Sometimes you will see rules with a selector that lists the HTML element selector along with the class:

```css
li.special {
  color: orange;
  font-weight: bold;
}
```

This syntax means "target any `li` element that has a class of special".

## color and background-color

Colors can be applied by using `color` and `background-color` (note that this must be the American English “color” and not “colour”).

A blue background and yellow text could look like this:

```css
h1 {
    color: yellow;   
		background-color: blue;
}

```

These colors might be a little too harsh, so you could change the code of your CSS file for slightly different shades:

```css
body {
    font-size: 14px;
    color: navy;
}

h1 {
    color: #ffc;
    background-color: #009;
}

```

Save the CSS file and refresh your browser. You will see the colors of the first heading (the `h1` element) have changed to yellow and blue.

You can apply the `color` and `background-color` properties to most HTML elements, including `body`, which will change the colors of the page and everything in it.

## Text formatting using css

### font-family

This is the font itself, such as Times New Roman, Arial, or Verdana.

### font-style

`font-style` states whether the text is italic or not. It can be `font-style: italic` or `font-style: normal`.

### text-transform

`text-transform` will change the case of the text.

- `text-transform: capitalize` turns the first letter of every word into uppercase.
- `text-transform: uppercase` turns everything into uppercase.
- `text-transform: lowercase` turns everything into lowercase.
- `text-transform: none` I’ll leave for you to work out.

**Example:**

```css
body {
    font-family: arial, helvetica, sans-serif;    font-size: 14px;}

h1 {
    font-size: 2em;}

h2 {
    font-size: 1.5em;}

a {
    text-decoration: none;}

strong {
    font-style: italic;    text-transform: uppercase;}
```

### Margin and Padding

`margin` and `padding` are the two most commonly used properties for spacing-out elements. A margin is the space outside something, whereas padding is the space inside something.

![Html%20and%20CSS%20c7204d15b835490a837f2fa7451de01d/Untitled.png](Html%20and%20CSS%20c7204d15b835490a837f2fa7451de01d/Untitled.png)

Change the CSS code for `h2` to the following:

```css
h2 {
    font-size: 1.5em;
    background-color: #ccc;
		margin: 20px;
		padding: 40px;
}

```

This leaves a 20-pixel width space around the secondary header and the header itself is fat from the 40-pixel width padding.

# Exercise :
create an Html page that looks the same like in the following example applying what you have learned Untill now.

<p align="center"><img src="https://i.imgur.com/xWsiIQP.png" height="500" alt="alt text" title="exercise 3"></p>
