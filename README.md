# RIME 小狼毫輸入工具實用配置

## 主要說明
1. 本配置基於RIME的Windows版本weasel（小狼毫），未包含mac版本
2. 本配置目的是改善RIME的使用操作以及擴展詞庫
3. 使用本配置請將檔案放置於RIME用戶文件夾

## 設置內容
設置內容參考RIME設置建議，皆存於`.custom.yaml`，不會影響主程式的內容，各檔案設置內容如下：

`default.custom.yaml`: 
1. 以Shift及Caps鍵切換中英文，並寫入
2. 以左右中括號`[]`進行換頁
3. 候選字數量設定為9個
4. 輸入法選項僅保留：朙月拼音-臺灣正體
5. 切換輸入法快捷鍵改為`` control+` ``

`luna_pinyin_tw.custom.yaml`:
1. 擴充詞庫設定，導向`luna_pinyin_tw.extende.yaml`
2. 設置模糊音
3. 設置特殊符號，導向`symbols.custom.yaml`

`luna_pinyin_tw.extende.yaml`:
1. 擴充詞典設定，導向`dicts`文件夾中的詞典

`symbols.custom.yaml`
1. 自訂特殊符號

`weasel.custom.yaml`
1. 自訂外觀