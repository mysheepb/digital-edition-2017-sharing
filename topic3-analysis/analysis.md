## 3. 文本分析的基本要素
* 文本處理
  * tokenization(標記化) (與 markup 不同）
  * normalization(正規化) / stemming(詞幹提取)
  * collation(對照/理序)
* 數位工具/程式語言


### tokenization
* 把文本分成最小具（完整）語義的單位
* 歐洲語言：以空白或標點符號分隔，但⋯⋯
  * John's -> John / 's
  * don't -> do / n't
  * l'hôtel -> l' / hôtel
  * aujourd'hui  
* 東亞語言（中日韓）：斷詞
  * DocuSky: http://docusky.digital.ntu.edu.tw


### normalization
* 方便分析（e.g. 統計、比較)
* check, checking, checked (stem: check)
* document, documents, documentation (stem: document)
* 不同的 [normalization](https://github.com/Pittsburgh-NEH-Institute/Institute-Materials-2017/blob/master/schedule/week_2/Normalization.ipynb)
  * [examples](https://github.com/Pittsburgh-NEH-Institute/Institute-Materials-2017/blob/master/schedule/week_2/Normalization_examples.ipynb)


### collation
* 比照同一作品的不同的抄本見證 manuscript witnesses
* 找出文本間不同之處
* 找出不同版本 editions 間修改之處
* 大、小的增、刪、改內容、改次序、⋯⋯等
* 引用、重寫
* example: [Frankenstein 「科學怪人／法蘭克斯坦」](https://github.com/ebeshero/Pittsburgh_Frankenstein/blob/master/collateXPrep/c56_textTableOutput/collation_C13.txt)


### 數位工具/程式語言
* [CollateX](https://collatex.net/) - **Python**
* Juxta
  * example: [L’Estrange’s 1870 edition of Mitford’s Letter to Benjamin Robert Haydon of Oct. 31, 1821 vs. Our Transcription from Manuscript](http://juxtacommons.org/shares/nDPeai)
* 編程 example: [斯拉夫語](http://pvl.obdurodon.org/browser.xhtml)

#### 人文學者（或任何人）學習編程
* [The Programming Historian](https://programminghistorian.org/)
* [Coding for Huamnists Book Series](http://coding.forhumanists.org/)
