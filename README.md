**高鐵自動訂票App**

目錄

一、	摘要…………………………..2

二、	研究動機與目標……….2

三、	研究方法及步驟……….2

四、	結論………………………….2

五、	參考資料………………….3

............................................................................................................................................................................................................................

一、	摘要

  藉由投入NLP與Web Crawler，由使用者以語音辨識控制，提升台灣高鐵購票速度、減少操作流程。

二、	研究動機與目標

  近來由於大眾運輸的成熟與通貨膨脹的影響，台灣高速鐵路使用率逐年成長。為提供購票者更為精簡、迅速的購票流程服務，故以投入語音辨識功能與自動化購票為目標進行本專題研究

三、	研究方法及步驟

(一)	  首先我們投入Selenium進行台灣高鐵網頁爬蟲，其特性為模擬使用者實際操作網頁之情境，可以讓使用者視覺化了解程式執行階段。

(二)	  接著採用Python套件SpeechRecognition偵測使用者中文語音，擷取關鍵字如時間、站點等，經由與Selenium爬取的資料比對並輸入到相關聯搜尋欄位。

四、	結論

目前偵測語言僅限中文，測試時因為團隊成員有僑生，出現口音差異導致關鍵字偵測偏差或錯誤之情況，該部分仍在巡炒解決方案。

五、	參考資料

1.Selenium with Python

2.SpeechRecognition 3.10.0

3.動態網頁爬蟲第一道鎖 — Selenium教學：如何使用Webdriver、send_keys(附Python 程式碼)

4.使用Python進行語音辨識(聲音轉文字)
