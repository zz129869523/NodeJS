# HTML 屬性

屬性提供了HTML元素的其他信息。

## HTML 屬性


- HTML 元素可以有**屬性**
- 屬性提供了元素**更多的信息**
- 屬性都寫在指定的**開始標籤**裡面
- 屬性是一個名字對一個值 就像 **名稱=“值”**

## lang 屬性

```
文檔的語言可以再 <html> 裡面聲明

lang 屬性聲明語言

聲明語言 對於 輔助功能應用程式（螢幕閱讀器）和 搜索引擎 來說是很重要的
```

``` html
<!DOCTYPE html>
<html lang="en-US">
  <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

  </body>
</html>
```


## title 屬性

```
HTML 段落定義為<p>

在這個例子中，<P>元件具有標題屬性。該屬性的值是" About W3Schools "：
```

### 範例

```  html
<p title="About W3Schools">
W3Schools is a web developer's site.
It provides tutorials and references covering
many aspects of web programming,
including HTML, CSS, JavaScript, XML, SQL, PHP, ASP, etc.
</p>
```
**當滑鼠移動到元素上時標題就會顯示出來**


## href 屬性

HTML 連結定義為< a>標籤. 連結的網址為 href屬性的值

### 範例

```html
<a href="http://www.w3schools.com">This is a link</a>
```
之後的教學會學到更多有關連結與< a>標籤的用法


## Size 屬性

```
HTML 圖像是使用 <img>標籤

The filename of the source (src), and the size of the image (width and height) are all provided as attributes:
```

### 範例

```html
<img src="w3schools.jpg" width="104" height="142">
```
圖像尺寸以像素為單位：width="104" 是指寬為104像素。

之後的教學會學到更多有關圖像與< img>標籤的用法

## alt 屬性

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
