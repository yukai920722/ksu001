# HTTP

- [Hypertext Transfer Protocol (HTTP)](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)
- [超文本傳輸協定](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)
  - HTTP是一種用於分佈式、協作式和超媒體訊息系統的應用層協定
![http](https://user-images.githubusercontent.com/90737336/138025593-498da267-7c8b-4a06-8217-fc4e53fffd72.png)
## HTTP Request

![HTTP_Request](https://user-images.githubusercontent.com/90737336/138025628-2715f601-c346-4a3d-81a8-c96f72173520.png)
- CRLF refers to the special character elements "Carriage Return" and "Line Feed."
These elements are embedded in HTTP headers and other software code to signify an End of Line (EOL) marker.
- Many internet protocols, including MIME (e-mail), NNTP (newsgroups) and, more importantly, HTTP, use CRLF sequences to split text streams into discrete elements.
- Web application developers split HTTP and other headers based on where CRLF is located.
- CRLF injection attack ==> Exploits occur when an attacker is able to inject a CRLF sequence into an HTTP stream.

## [HTTP Request method請求方法](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

- [HTTP request methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)

|方法 | 說明 |
| -------|  -------|
|GET|使用GET方法應該只用在讀取資料|
|HEAD|與GET方法一樣，都是向伺服器發出指定資源的請求。只不過伺服器將不傳回資源的本文部份。它的好處在於，使用這個方法可以在不必傳輸全部內容的情況下，就可以取得其中「關於該資源的訊息」（元訊息或稱元資料）。|
|POST|向指定資源提交資料，請求伺服器進行處理（例如提交表單或者上傳檔案）。資料被包含在請求本文中。|
|PUT|向指定資源位置上傳其最新內容。|
|DELETE|請求伺服器刪除Request-URI所標識的資源。|
|TRACE|回顯伺服器收到的請求，主要用於測試或診斷。|
|OPTIONS|這個方法可使伺服器傳回該資源所支援的所有HTTP請求方法。|
|CONNECT|HTTP/1.1協定中預留給能夠將連接改為隧道方式的代理伺服器。通常用於SSL加密伺服器的連結（經由非加密的HTTP代理伺服器）。|

## HTTP Response

![HTTP_Response](https://user-images.githubusercontent.com/90737336/138024758-2d523b82-8a68-42ef-8059-5bbefc549b98.png)

## [HTTP Status Code(HTTP狀態碼)](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)

| 類別 |  說明  | 
|  ---- |  -----  | 
| 1xx|   訊息   | 
| 2xx|   成功   | 
| 3xx| 重新導向 | 
| 4xx| 客戶端錯誤 | 
| 5xx| 伺服器錯誤 | 
