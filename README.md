# 午餐小幫手 網頁版

打開就能用：<https://derliang.github.io/lunch-helper-web/>

這個 repo 只放組建好的網頁（GitHub Pages 發布用），請不要直接修改。原始碼在私有的 Lunch-Helper repo，用 `node web/build.js` 產生後再複製過來。

- 給負責訂餐的人用：建店家與菜單、開訂購單、幫大家代點、統計份數與金額、收錢勾選、儲值記帳。
- 資料是一份 Excel（「午餐小幫手資料.xlsx」），存在自己的裝置、電腦上的檔案，或自己的 Google 雲端硬碟（跨裝置同步）。
- 程式只申請 `drive.file` 權限，只能存取它自己建立的檔案。開發者沒有伺服器，不會收到任何資料。
