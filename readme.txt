Our purpose:
* 本程式可以提供使用者針對現有組織進行簡單分類，以達到在疫情下分組上班的目的

Steps:
* 下載分組app(無圖版)_v0.4.7z後解壓縮
* 運行grouping.exe
* 等程式跳出input the data source:後開始輸入資訊
* excel轉csv檔
* 輸入設定
* 完成後打開結果csv

User Manual:
* 輸入資料由excel另存csv檔時，建議以utf8編碼儲存
* 本程式需要輸入三個變數:
	- input the data source: => 請輸入完整檔案地址(ex: C:\Users\桌面\example.csv)
	- input the data destination: => 請輸入完整檔案地址(ex: C:\Users\桌面\result.csv)，請務必確認該路徑沒有重複名稱的檔案
	- input how many group should be divided: => 請輸入要分類的組別
* 請注意，輸入資料前必須輸入清單沒有重複的人名
* 資料檔案第一欄必須是可辨識的名稱或是代號
* 資料檔案第二欄後為使用者自訂義的資料欄位，使用者可根據部門、職級、樓層...進行自訂義的調整
* 若遇到任何問題歡迎來信至leoweng9@gmail.com

@Authored by Leo_Weng/@Powered by Python
