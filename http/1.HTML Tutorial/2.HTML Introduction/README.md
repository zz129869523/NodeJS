#HTML 介紹

##什麼是HTML?

- HTML 分別代表 超 (**H**yper)文本 (**T**ext) 標記 (**M**arkup) 語言 (**L**anguage)

- 標記語言 是一種 **標記標籤**

- 使用 HTML標籤 來描述 **HTML文檔**

- 每個不同的 HTML標籤 描述不同的文檔內容

``` javascript
<!DOCTYPE html>
<html>

	<head>

		<title>Page Title</title>
	</head>

	<body>

		<h1>My First Heading</h1>
		<p>My first paragraph.</p>

	</body>
</html>
```
[HTML 範例](./HTML Introduction.html)
##範例解釋
```
該 DOCTYPE 聲明定義了文檔類型為HTML
<html>  和 </html> 之間的文本 描述的是一個 HTML文檔
<head>  和 </head> 之間的文本 提供了關於文檔的信息
<title> 和 </title>之間的文本 顯示文檔標題
<body>  和 </body> 之間的文本 為 可見頁面內容
<h1>    和 </h1>   之間的文本 為 標題
<p>     和 </p>    之間的文本 為 段落
```

##HTML標籤

被 **尖括號** 包住的 關鍵字（標籤名） 就是 HTML標籤

```
<標記名> 內容 </標記名>
```

```
HTML標籤 通常都是 一對 的 就像 <p> 和 </p>

第一個標籤是 開始標籤，第二個標籤是 結束標籤

結束標籤 和 開始標籤 很像，但在 標籤名 前多了一條 斜杠
```

##Web瀏覽器

Web瀏覽器的目的（瀏覽器，IE，Firefox和Safari）是讀取HTML文檔並顯示它們。

瀏覽器不顯示HTML標籤，但用它們來決定如何顯示文件

![html](http://www.w3schools.com/html/img_chrome.png)

##HTML頁面結構

下面是HTML的頁面結構

***

- < html>

  - < head>

    - < title> 頁面標題 </title>

  - < /head>

  - < body>

    - < h1> 這是一個標題 </h1>

    - < p> 這是一個段落。</p>
    - < p> 這是另一個段落 </p>
  - < /body>

- < /html>

## <！DOCTYPE> 聲明

<！DOCTYPE>的聲明有助於正確顯示網頁瀏覽器。

在網絡上有不同的文件類型。

要正確顯示文檔，瀏覽器必須知道類型和版本。

DOCTYPE聲明是不區分大小寫。所有例子都是可以接受的

``` javascript
<!DOCTYPE html>

<!DOCTYPE HTML>

<!doctype html>

<!Doctype Html>
```

## 常見的聲明

### HTML5

```javascript
<!DOCTYPE html>
```

### HTML 4.01

```javascript
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```

### XHTML 1.0

```javascript
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

## HTML版本

由於網絡初期出現了許多HTML的版本

Version | Year
-|-
HTML | 1991
HTML 2.0 | 1995
HTML 3.2 | 1997
HTML 4.01 |	1999
XHTML | 2000
HTML5 | 2014
