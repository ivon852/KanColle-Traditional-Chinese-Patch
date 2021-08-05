# 艦隊收藏中文化
Traditional Chinese Patch for Kancolle.\
艦隊收藏介面中文化，跟魔改原理很類似的模組。\
UI翻譯進度: 90%，更新至2021/07/24基地航空隊擴充更新。\
每週會跟英文版確認一次並更新翻譯，有任何建議歡迎發Issue。

## 使用方法
##### 安裝KCCacheProxy
請參考[作者的影片](https://www.youtube.com/watch?v=Dog1zKAAWeI)了解安裝，並為瀏覽器設置proxy。

##### 導入這個模組
勾選KCCP裡的"Enable Asset Modifier"，接著再點選Add a patcher，選取下載好的ZHTW-patch.mod.json。

## 未翻譯的部分
- img/battle
- kcs2/resource/下的map、world、worldselect。
- 裝備名稱圖卡 (位於kcs2/resources/slots/)
- 艦娘名稱 (位於kcs2/js/main.js/ignore-raw_text_translations/ignore-_ships.json)
- 裝備名稱 (位於kcs2/js/main.js/ignore-raw_text_translations/ignore-_equips.json)

## 致謝
此模組是基於[InochiPM的KanColle-English-Patch-KCCP](https://github.com/InochiPM/KanColle-English-Patch-KCCP)專案製作，部分中文翻譯來自kc3和艦娘百科。\
以下是原始致謝列表。\
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
