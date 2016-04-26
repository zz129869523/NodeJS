# HTML元素
HTML文件是由HTML元素所組成的。

## HTML元素
HTML元素都寫有一個開始標籤和結束標籤，內容在這兩者之間：
```html
<開始標記>內容</結束標籤>
```
HTML元素都是由開始標籤和結束標籤組成(有些標籤只有開始標籤)：
```html
<p>我的第一個HTML段落</p>
```
## 巢狀的HTML元素
HTML元素可以有巢狀（元素包含元素）。
所有HTML文件由巢狀的HTML元素組成。
這個例子包含4個HTML元素：
```
<!DOCTYPE html>                       <!--聲明這文件是HTML文件-->
<html>                                <!--定義整個文件-->
<body>                                <!--定義文件主體-->

<h1>My First Heading</h1>             <!--<標題開始標籤>內容</標題結束標籤>-->

<p>My first paragraph.</p>            <!--<段落開始標籤>內容</段落結束標籤>-->

</body>                               <!--文件主體結束標籤-->
</html>                               <!--文件結束標籤-->
```
## 空的HTML元素
沒有內容的HTML元素被稱為空元素。
結果就是沒有結束標籤的空元素。
```html
<br>                                  <!--定義換行-->
```
HTML5不需要所有元素都被關閉。但是如果你想嚴格的驗證，或者你需要讓XML解析器讀取你的文件，應關閉所有的HTML元素。

## HTML提示：使用小寫標籤
HTML標籤是不區分大小寫。
HTML5標準不要求小寫的標籤，但建議在HTML4小寫，並要求更嚴格的文件類型，如XHTML小寫。