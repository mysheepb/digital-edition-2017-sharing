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


### normalization
* 方便分析（e.g. 統計、比較)
* check, checking, checked (stem: check)
* document, documents, documentation (stem: document)
* 不同的normalization
  * [exmaples](https://github.com/Pittsburgh-NEH-Institute/Institute-Materials-2017/blob/79a0f05e641e954ae8ecd1396817478544aafcbd/schedule/week_2/computational_pipeline.md)

### collation
* 比照同一作品的不同的抄本 witnesses
* 找出文本間不同之處
* 找出不同版本 editions 間修改之處
* 大、小的增、刪、改內容、改次序、⋯⋯等
* 引用、重寫
* example: [L’Estrange’s 1870 edition of Mitford’s Letter to Benjamin Robert Haydon of Oct. 31, 1821 vs. Our Transcription from Manuscript](http://juxtacommons.org/shares/nDPeai)
