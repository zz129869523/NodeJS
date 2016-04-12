# HTML Attributes

Attributes provide additional information about HTML elements.

## HTML Attributes

```
HTML elements can have attributes
Attributes provide additional information about an element
Attributes are always specified in the start tag
Attributes come in name/value pairs like: name="value"
```
## The lang Attribute

```
The document language can be declared in the <html> tag.

The language is declared in the lang attribute.

Declaring a language is important for accessibility applications (screen readers) and search engines:
```

``` javascript
<!DOCTYPE html>
<html lang="en-US">
  <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

  </body>
</html>
```

The first two letters specify the language (en). If there is a dialect, use two more letters (US).

## The title Attribute

```
HTML paragraphs are defined with the <p> tag.

In this example, the <p> element has a title attribute. The value of the attribute is "About W3Schools":
```

### 範例

```  javascript
<p title="About W3Schools">
W3Schools is a web developer s site.
It provides tutorials and references covering
many aspects of web programming,
including HTML, CSS, JavaScript, XML, SQL, PHP, ASP, etc.
</p>
```

Note	When you move the mouse over the element, the title will be displayed as a tooltip.

## The href Attribute

HTML links are defined with the <a> tag. The link address is specified in the href attribute:

### 範例

```Javascript
<a href="http://www.w3schools.com">This is a link</a>
```

```
You will learn more about links and the <a> tag later in this tutorial.
```

## Size Attributes

```
HTML images are defined with the <img> tag.

The filename of the source (src), and the size of the image (width and height) are all provided as attributes:
```

### 範例

```Javascript
<img src="w3schools.jpg" width="104" height="142">
```

The image size is specified in pixels: width="104" means 104 screen pixels wide.

You will learn more about images and the <img> tag later in this tutorial.

## The alt Attribute

The alt attribute specifies an alternative text to be used, when an HTML element cannot be displayed.

The value of the attribute can be read by "screen readers". This way, someone "listening" to the webpage, i.e. a blind person, can "hear" the element.

### 範例

``` javascript
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```

## We Suggest: Always Use Lowercase Attributes

The HTML5 standard does not require lower case attribute names.

The title attribute can be written with upper or lower case like Title and/or TITLE.

W3C recommends lowercase in HTML4, and demands lowercase for stricter document types like XHTML.

Note	Lower case is the most common. Lower case is easier to type.
At W3Schools we always use lower case attribute names.

## We Suggest: Always Quote Attribute Values

The HTML5 standard does not require quotes around attribute values.

The href attribute, demonstrated above, can be written as:

### 範例

```javascript
<a href=http://www.w3schools.com>
```
W3C recommends quotes in HTML4, and demands quotes for stricter document types like XHTML.

Sometimes it is necessary to use quotes. This will not display correctly, because it contains a space:

### 範例

```javascript
<p title=About W3Schools>
```

Note	Using quotes are the most common. Omitting quotes can produce errors.
At W3Schools we always use quotes around attribute values.

## Single or Double Quotes?

Double style quotes are the most common in HTML, but single style can also be used.

In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:

```javascript
<p title='John "ShotGun" Nelson'>
```
Or vice versa:
```javascript
<p title="John 'ShotGun' Nelson">
```

## Chapter Summary

- All HTML elements can have attributes
- The HTML title attribute provides additional "tool-tip" information
- The HTML href attribute provides address information for links
- The HTML width and height attributes provide size information for images
- The HTML alt attribute provides text for screen readers
- At W3Schools we always use lowercase HTML attribute names
- At W3Schools we always quote attributes with double quotes

## HTML Attributes

Below is an alphabetical list of some attributes often used in HTML:

Attribute|	Description
-|-
alt	|Specifies an alternative text for an image
disabled	|Specifies that an input element should be disabled
href|	Specifies the URL (web address) for a link
id|	Specifies a unique id for an element
src	|Specifies the URL (web address) for an image
style	|Specifies an inline CSS style for an element
title|	Specifies extra information about an element (displayed as a tool tip)

A complete list of all attributes for each HTML element, is listed in our: <a href="http://www.w3schools.com/tags/default.asp">HTML Tag Reference.</a>
