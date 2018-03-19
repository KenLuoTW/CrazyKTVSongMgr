# CrazyKTV 加歌程式
CrazyKTV 加歌程式是基於 CrazyKTV 卡拉OK點歌軟體的歌庫管理工具,主要因為 CrazyKTV 原本所採用的 GodLiu 加歌程式擁有許多問題且已停止開發,所以才重新撰寫了這個加歌程式。經過將近一年的修改,已將加歌程式所需要的功能幾乎都實作了出來,並且也對程式做了許多除錯及優化,以確保資料的正確性及使用效率,目前已足以拿來實際運用。

![CrazyKTV 加歌程式](https://raw.githubusercontent.com/wiki/KenLuoTW/CrazyKTVSongMgr/images/CrazyKTV_SongMgr01.png)

## 功能特色
* 在操作上衍生了原本 GodLiu 加歌程式的使用習慣,讓舊用戶無需學習即能輕易上手。
* 可以自訂加歌時所限定的影音檔格式,無需擔心自訂格式或未來新穎影音格式的支援。
* 擁有『自動搬移/自動複製/不搬移不複製/歌庫監視』4種加歌模式,充分滿足用戶的需求。
* 歌曲編號支援5碼及6碼編碼位數,不會產生歌曲編號不夠用的問題。
* 支援加入自訂的歌曲類別,用以注釋歌曲或分類不同版本的同一首歌。
* 加歌速度在目前 CrazyKTV 相關加歌程式中最快。
* 擁有最智能的歌曲辨識方式,可在多種不同的歌庫結構裡正確辨識出歌曲資料。
* 分析歌曲時支援簡易的簡轉繁功能,可直接辨識以簡體中文命名的歌曲檔案。
* 擁有強大的歌庫查詢及管理系統,可直接查詢或修改有問題的歌曲資料。
* 擁有實用的歌手管理系統,可自行增刪所需要的歌手資料。
* 擁有完整的歌庫維護功能,既使重新加歌或歌庫轉移,都能保留想要的歌曲資料。
* 擁有使用 VLC 程式庫的內建播放器,可播放大部份的影音格式。
* 擁有自動更新功能,免去有更新時還要用戶自行下載並解壓檔案的麻煩。

## 系統需求
* Windows XP / Windows 7 / Windows 8 / Windows 10 (32bit 或 64bit)
* Microsoft .NET Framework 4.0 以上之版本

**備註:**

Windows XP 僅能安裝 [Microsoft .NET Framework 4.0](http://www.microsoft.com/zh-tw/download/details.aspx?id=17851) 版本。

Windows 7 可以直接安裝 [Microsoft .NET Framework 4.6.1](https://www.microsoft.com/zh-TW/download/details.aspx?id=49981) 版本。

Windows 8 內建 .NET 4.0 版本,你也可以升級為 [Microsoft .NET Framework 4.6.1](https://www.microsoft.com/zh-TW/download/details.aspx?id=49981) 版本。

Windows 10 內建 .NET 4.6 版本,你也可以升級為 [Microsoft .NET Framework 4.6.1](https://www.microsoft.com/zh-TW/download/details.aspx?id=49981) 版本。

## 下載與使用
* 下載位址: [CrazyKTV_WebUpdater.exe](https://github.com/CrazyKTV/WebUpdater/raw/master/CrazyKTV_WebUpdater/UpdateFile/CrazyKTV_WebUpdater.exe)

**使用說明:**

1. 建立 CrazyKTV 資料夾
2. 將 CrazyKTV_WebUpdater.exe 拷貝至 CrazyKTV 資料夾
3. 執行 CrazyKTV_WebUpdater.exe 檔案以自動下載所有檔案
4. 執行 CrazyKTV_SongMgr.exe 檔案 (加歌程式)

## 功能需求或問題回報
* 如果你有註冊 GitHub 帳號,可直接在 [Issues](https://github.com/KenLuoTW/CrazyKTVSongMgr/issues) 裡回報。
* 如果你沒有 GitHub 帳號,也可直接在 [CrazyKTV 臉書專頁](https://www.facebook.com/NewCrazyKTV) 裡回報。

## 編譯環境及建置
* Windows 10
* Microsoft Visual Studio Community 2015

**洐生此專案**

網址: https://github.com/KenLuoTW/CrazyKTVSongMgr.git

1. 開啟 Microsoft Visual Studio Community 2015
2. 在管理連接裡的本機 Git 儲存機制複製上面的網址
3. 開啟 CrazyKTV_SongMgr.sln

