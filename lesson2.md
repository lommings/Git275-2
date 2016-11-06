# git 指令與功能

| git 指令       | 功能              |
| ------------- |:-----------------:|
| git add       | 把檔案放置 staging  |
| git commit    | 把 staged 檔案放置  |
| git status    | 檢查工作路徑目前的狀態|
| git log       | 檢查工作紀錄        |

出現下列錯誤：
-----------
**fatal: remote origin already exists.**
解決方法：
先執行底下指令刪除，再重新執行「$ git remote add origin...」。
$ git remote rm origin
