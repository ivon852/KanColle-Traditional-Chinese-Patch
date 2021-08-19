# 艦隊收藏中文化
Traditional Chinese Patch for Kancolle.\
艦隊收藏介面中文化，透過KCCProxy運作，可搭配poi、74式電子觀測儀、或單純瀏覽器運作。\
![Title](https://i.imgur.com/mUIReZV.jpg)
翻譯進度更新至2021/08/20夏活。\

## 使用方法
### 安裝KCCacheProxy
請參考[作者的影片](https://www.youtube.com/watch?v=Dog1zKAAWeI)。

### 導入這個模組
按右上角的Code下載這個專案的壓縮檔，解壓縮。/
勾選KCCP裡的"Enable Asset Modifier"，接著再點選Add a patcher，選取解壓縮資料夾的ZHTW-patch.mod.json，然後刪除瀏覽器快取。

## 致謝
此模組是基於[InochiPM的KanColle-English-Patch-KCCP](https://github.com/InochiPM/KanColle-English-Patch-KCCP)專案製作，部分中文翻譯來自kc3和艦娘百科。\
原始致謝列表可至該頁面查看。

## 開發相關
每週會跟英文版確認進度並更新翻譯，有任何建議歡迎發Issue。\
可切換至dev分支下載含有psd檔的壓縮包進行修改。

### 使用到的字體
除了dev分支的psd檔案外，這個專案還使用了以下字體，需自行安裝:
- A-OTF リュウミン Pr6n (R為基礎，粗體一般M就夠)
- A-OTF ゴシックMB101 Pr6N (EB-KL為主，最多加上仿粗體)

### 未翻譯的部分
- 裝備名稱圖卡 (位於kcs2/resources/slots/)
- 艦娘名稱文本 (位於kcs2/js/main.js/ignore-raw_text_translations/ignore-_ships.json)
- 裝備名稱文本 (位於kcs2/js/main.js/ignore-raw_text_translations/ignore-_equips.json)

### 待修正列表
- kcs2\img\battle\battle_telop\txt_start.png 參照原本的noise
- world的字體加寬
- skin3的UI對齊
- 任務返回的按鈕對齊