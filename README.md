# Python-Stock_Price_Comparison-Demo

###### tags `Python`

## 專案動機
- 近期正在進行軟體測試面試，有鑑於工作技能需要Python，因此開立此專案作為面試Demo使用。

## 專案目標
- 同時分析比較任意兩檔台灣股票的近一年內的每月收盤價作為投資理財的參考依據。
- 將網路爬蟲、Pandas資料分析與視覺化、Tkinter桌面應用程式彙整出一個專案，作為Python線上自學課程總結。

## 專案使用Ptyhon套件
- 本次專案有使用到下列Ptyhon套件:
    - requests:  網頁爬蟲使用，模擬發出 HTTP GET 請求到 server 伺服器端，取得回傳了該網頁的 HTML 內容。
    - Beautiful Soup: 網頁爬蟲使用，使用 CSS 選擇器來對回傳 HTML 進行解析，取到想要的元素內容資料。
    - time: 網頁爬蟲使用，設定每次爬取網頁時可以 sleep 休息。
    - csv: 清理資料與資料格式化，將 list (裡面是 dict 每月資料)轉成 .csv 檔案來儲存。
    - pandas: 資料分析，處理csv資料轉成DataFrame。
    - matplotlib.pyplot: 視覺化，將DataFrame資料繪製成數據圖。
    - tkinter: GUI介面，可設定桌面視窗與對應標籤元件。
    - Image,ImageTk: 處理圖片，取代tkinter內建Photoimage，ImageTk.Photoimage 建立 tk 圖片物件(支援性更佳)。

## 專案執行環境
- 本項專案在下列環境中執行:
    - OS: Windows 10
    - Python: Python 3.11.0
    - Visual Studio Code: 1.81.1
    - Python 3rd Party Packages: 
        - 可按照下列Python pip指令完成Packages安裝:
            - pip install requests
            - pip install bs4
            - pip install python-time
            - pip install python-csv==0.0.10
            - pip install pandas
            - pip install matplotlib
            - pip install tk
            - pip install Pillow
## 程式介面與功能規劃
- ![image](https://github.com/steve50207/Python-Stock_Price_Comparison-Demo/blob/main/png/%E7%A8%8B%E5%BC%8F%E4%BB%8B%E9%9D%A2%E8%88%87%E5%8A%9F%E8%83%BD%E8%A6%8F%E5%8A%83.PNG)
      
## 系統架構規劃
- ![image](https://github.com/steve50207/Python-Stock_Price_Comparison-Demo/blob/main/png/%E7%B3%BB%E7%B5%B1%E6%9E%B6%E6%A7%8B%E8%A6%8F%E5%8A%83.PNG)
    
## 執行結果
- 比較緯創資通(3231)&緯創軟體(4953)近一年的股價變化長條圖
    - 執行前:
        - ![image](https://github.com/steve50207/Python-Stock_Price_Comparison-Demo/blob/main/png/%E5%9F%B7%E8%A1%8C%E5%89%8D.PNG)
    - 執行後:
        - ![image](https://github.com/steve50207/Python-Stock_Price_Comparison-Demo/blob/main/png/%E5%9F%B7%E8%A1%8C%E5%BE%8C.PNG)