# KanColle-Traditional-Chinese-Patch
Traditional Chinese Patch for Kancolle.\
艦隊收藏中文化。即時將遊戲中的字串替換，達到翻譯文本的功效。\
UI翻譯進度: 75%，活動部分則是更新至2021年春活的翻譯。每週更新進度。

## 使用方法
##### 安裝KCCacheProxy
請參考[作者的影片](https://www.youtube.com/watch?v=Dog1zKAAWeI)了解安裝，並為瀏覽器設置proxy。

##### 導入這個模組
勾選KCCP裡的"Enable Asset Modifier"，接著再點選Add a patcher，選取下載好的ZHTW-patch.mod.json。

## 需修改的部分
- resources/資料夾下的圖片除useitem/外尚未翻譯。
- img/下的album、arsenal、battle資料夾的圖片使用的字體錯誤。

## 未翻譯的部分
- 艦娘名稱
- 裝備名稱

## 致謝
此模組是基於[InochiPM的KanColle-English-Patch-KCCP](https://github.com/InochiPM/KanColle-English-Patch-KCCP)專案製作，大部分中文翻譯來自kc3和艦娘百科。
以下是原始致謝列表。
Special Thanks
To Tibo for implementing new ways to patch the game's textures with KCCacheProxy,\
as well as for making some code specially to patch raw text in a stable way.\
To Dark Sentinel for contributing (LBAS menu aircraft names, world icons, server banners).\
To Amelek for the chuuha/taiha cut-in texture jigsaw splitter.\
To Globalnet for the quick updater.\
To the EN wiki staff and the kc3 staff for providing a good part of the translations.\
To atikabubu, Althea, Dotsidious, TerminaHeart, LeftistTachyon\
and all the others in the Discord server for regularly suggesting\
new things to fix or translate in the patch.
