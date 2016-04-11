#HTML 介紹

##什麼是HTML?

- HTML 分別代表 超 (__H__yper)文本 (__T__ext) 標記 (__M__arkup) 語言 (__L__anguage)

- 標記語言 是一種 __標記標籤__

- 使用 HTML標籤 來描述 __HTML文檔__

- 每個不同的 HTML標籤 描述不同的文檔內容

'''bash
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
'''

##範例解釋

- 該 __DOCTYPE__ 聲明定義了文檔類型為HTML
- __<html>__  和 __</html>__ 之間的文本 描述的是一個 HTML文檔
- __<head>__  和 __</head>__ 之間的文本 提供了關於文檔的信息
- __<title>__ 和 __</title>__之間的文本 顯示文檔標題
- __<body>__  和 __</body>__ 之間的文本 為 可見頁面內容
- __<h1>__    和 __</h1>__   之間的文本 為 標題
- __<p>__     和 __</p>__    之間的文本 為 段落


##HTML標籤

被 __尖括號__ 包住的 關鍵字（標籤名） 就是 HTML標籤

'''bash
<標記名>內容 </標記名>
'''

- __HTML標籤__ 通常都是 __一對__ 的 就像 <p> 和 </p>

- 第一個標籤是 __開始標籤__，第二個標籤是 __結束標籤__

- 結束標籤 和 開始標籤 很像，但在 __標籤名__ 前多了一條 __斜杠__

##Web瀏覽器

Web瀏覽器的目的（瀏覽器，IE，Firefox和Safari）是讀取HTML文檔並顯示它們。

瀏覽器不顯示HTML標籤，但用它們來決定如何顯示文件

![html](http://www.w3schools.com/html/img_chrome.png)

##HTML頁面結構

下面是HTML的頁面結構

___

- <html>
  - <head>
    - <title> 頁面標題 </title>

  - </head>
  - <body>

    - <h1> 這是一個標題 </h1>
    - <p> 這是一個段落。 </p>
    - <p> 這是另一個段落。 </p>

  - </body>
- </html>

## <！DOCTYPE> 聲明

<！DOCTYPE>的聲明有助於正確顯示網頁瀏覽器。

在網絡上有不同的文件類型。

要正確顯示文檔，瀏覽器必須知道類型和版本。

DOCTYPE聲明是不區分大小寫。所有例子都是可以接受的

'''
<!DOCTYPE html>

<!DOCTYPE HTML>

<!doctype html>

<!Doctype Html>
'''

## 常見的聲明

### HTML5

'''
<!DOCTYPE html>
'''

### HTML 4.01

'''
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
'''

### XHTML 1.0

'''
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
'''

## HTML版本

由於網絡初期出現了許多HTML的版本

Version  	| Year
 -        |  -
HTML    	| 1991
HTML 2.0  |	1995
HTML 3.2	| 1997
HTML 4.01 |	1999
XHTML   	| 2000
HTML5	    | 2014
