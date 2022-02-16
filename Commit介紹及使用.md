# Commit介紹
commit是將add到暫存區中的項目差異提交到本地儲存庫，並留下訊息描述此次提交做出了哪些改變，有利於之後需要將檔案還原時，較容易找到應該要還原到的時間點。
# Commit使用方法
## 先把變更add進暫存區
    $git add <檔案名稱>     #檔案名稱可以換成'.'代表所有檔案
## 使用commit儲存變更並留下訊息
    $git commit -m "<訊息>"
# 用Log可以查看所有Commit留下的訊息
    $git log
# 想查看檔案是否Add或是Commit狀態
    $git status