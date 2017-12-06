## 2. 基礎:文本預備
1. [文本標籤:TEI (Text Encoding Initiative) 標準](#文本標籤tei-text-encoding-initiative-標準)
1. [認識 XML (eXtensible Markup Language 可延伸標記語言)](#認識-xml-extensible-markup-language-可延伸標記語言)

### 文本標籤:TEI (Text Encoding Initiative) 標準
是以XML語言來標記文獻檔案的一個標準。


### 認識 XML (eXtensible Markup Language 可延伸標記語言)
是用來定義markup language（標記語言）的一種標準。


### 什麼是 markup（標記）？
* 在文字上加上標記，可以增添純文字不能表達的資料（information）
* 目的：我們（意會而）知道的，（以明示的方式）讓**機器**知道。
  * [人手標記的《成唯識論》範本](http://kobayashi.jimbou.net/catalog/images/products/c2200/34672.jpg)
* 兩主要類別：「排版或顯示格式」的標記 &「資料結構或內容」的標記 
  * 「排版或顯示格式」標記：e.g. `\textcolor{red}{-1000元}`
    * HTML, TeX, etc.
  * 「資料結構或內容」標記：e.g. `<measure unit="TWD" value="-1000">負債臺幣壹仟圓</measure>`
    * XML


### XML 特色
* 自訂標籤（tag）意義（不同HTML等有一套既定的標籤）
* 標籤資料結構或內容而非顯示格式：可以在不同媒體或用途上有不同顯示格式
* 開始標籤 <_element\_name_> 和結束標籤 <**/**_element\_name_>
* element 可以有一個或多個 attribute


## 參考資料
* 周邦信，〈標記語言的應用〉，《佛教圖書館館訊》，第24期。<http://www.gaya.org.tw/journal/m24/24-main5.htm>
* James Cummings, “An Introduction to Markup, XML, TEI, and the oXygen XML Editor,” Prezi presentation, [https://prezi.com/jiwc-yg9wmlq/an-introduction-to-markup-xml-tei-and-the-oxygen-xml-editor/](https://prezi.com/jiwc-yg9wmlq/an-introduction-to-markup-xml-tei-and-the-oxygen-xml-editor/).
