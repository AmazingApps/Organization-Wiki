#### Windows 貢獻指引

首先，對於任何貢獻表示歡迎及感謝。閱讀以下內容將進一步協助本項目變得更好：

（當然，如果您無法理解下列內容，也不必在貢獻時有所顧忌，這畢竟只是建議）

* 當您創建一個關於添加新應用程式的 issue 時：
    1. 請確認該應用程式符合 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 當中的條件
    2. 表明建議添加的分類並附註官網連結
    3. 建議提出簡潔、概括性的描述
    4. 建議盡量提出相關資訊，如是否免費、是否開源、是否為可攜式軟體、多語言支援（若僅支援少數語言則建議表明具體語言）、是否使用命令列操作等

* 當您創建一個移除應用程式的 issue 時：
    1. 請具體指出應用程式違反 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 中的哪幾項
        * 也可以指出符合 [黑名單](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/blacklist.md) 條件的哪些項目，若符合還會考慮放入黑名單
    2. 其他違反行業基本守則的行為同樣會被考慮
 
###### **如果您不熟悉 Markdown 語法格式，請勿創建 pull request，請新建一個 issue**

* 當您創建一個添加新應用程式的 pull request 時：
    1. 請確認該應用程式符合 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 當中的條件
    2. 請註明相關資訊：
        * 請用第三級標題寫應用程式名稱，並在程式名處附帶官網連結，隨後請根據具體資訊添加標識 logo
            * 如果位於官網主頁的下載按鈕指向一個二級站點，且安裝包 URL 位於該站點，請使用第六級標題在第二列分開標註官網與下載頁面（此時請勿在第一列的程式名處附帶官網連結）
            * 標識 logo 位於 `assets` 目錄下，使用相對路徑表示，文件請帶副檔名
                * 如果因程式特定介面語言而需要新 logo 的請 [聯繫 owner](https://t.me/EMLVIRUS)
                * 標識 logo 請按照順序排列：免費→開源→支援的語言→可攜式→跨平台→命令列操作
                * 若該程式開源，請使用圖片的 title 屬性註明開源協議、託管站點與開源地址，title 格式為：開源協議 @託管站點: 開源地址
       * 使用概括性語言描述程式功能：對於一個 awesome list 而言，** 完整簡潔的概括 ** 至關重要
    3. 如果該程式創建人具有中國國籍（包含港澳台地區），除非創建人另有要求，請複製到 [國產應用程式目錄](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/china-apps.md) 中
    4. 如果該程式存在以下情況，請在程式描述後另轉一列添加額外描述：
        1. 網路下載或綑綁其它軟體安裝包，但目標軟體具有完善卸載功能且無害、無明顯惡意行為的
        2. （仍在維護但）長期未更新且無明顯 bug 的；若不清楚該程式是否仍被維護，請使用刪除線表示。
        3. 除 C++、.Net framework 等之外需要其它額外運行庫的，如 Java
    5. 在 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 的計數 badge 處 + 1，並在 [acknowledgement](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/acknowledgement.md) 處添加您的資訊
        * **如果您不清楚具體操作法法，請到此為止**

* 當您創建一個移除應用程式的 pull request 時：
    1. 如果該應用程式符合 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 當中的爭議條件，請添加刪除線並移除官網連結
    2. 如果該程式符合 [黑名單](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/blacklist.md) 的條件，請將其在分類中刪除，添加到黑名單，並指出符合哪些黑名單標準
    3. 在 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 的計數 badge 處 - 1，並在 [acknowledgement](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/acknowledgement.md) 處添加您的資訊
        * **如果您不清楚具體操作法法，請到此為止**
