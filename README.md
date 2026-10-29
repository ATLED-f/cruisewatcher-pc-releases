# StarDream PC 發布

作者 Eric。僅提供 Windows 免安裝分享套件、更新資訊與校驗檔，不包含原始碼、會員資料或內部報告。

## v0.8.55 · 精簡更新視窗

[下載分享套件](https://github.com/ATLED-f/cruisewatcher-pc-releases/releases/download/v0.8.55/CruiseWatcher_v0.8.55_portable.zip)

程式更新視窗為 420×200，僅顯示版本、狀態與必要操作，不顯示改版內容。

EXE 固定使用 **CruiseWatcher.exe**。版本號保留於 ZIP、版本資料夾、程式內與 Windows 檔案內容。

### 舊版首次切換

關閉舊程式，將新版完整解壓到原本 EXE 所在資料夾，保留自己的 CruiseWatcherData，再開啟 CruiseWatcher.exe，將捷徑改指向它一次。不要只重新命名舊 EXE。之後沿用固定入口與一鍵更新。

舊更新器使用含版本檔名的白名單，latest.json 頂層保留相容 v0.8.53，避免送出不相容套件；新版讀取 fixed_executable_release。兩通道均使用固定倉庫 HTTPS 與 SHA-256 校驗。

Windows 免安裝，需 Google Chrome，會員自行登入及完成驗證。更新後需重新確認登入，瀏覽器資料保留。SHA-256 為完整性核對，未加入獨立發布簽章。程式不代按最終訂房或付款。
