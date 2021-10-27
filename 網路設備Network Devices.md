# 網路設備Network Devices

![網路設備](https://user-images.githubusercontent.com/90737336/138015978-c835e328-cff7-4647-8835-c3fe17f86542.png)

## [router 路由器](https://en.wikipedia.org/wiki/Router_(computing))

- 路由器是屬於OSl第三層的產品，交換器是OSI第二層的產品。
- 路由器就是連接兩個以上個別網路(段)的裝置 ==>  左網段(192.168.1.0/24)---路由器---右網段(192.165.8.0/24)。
- [tp-link 路由器](https://www.tp-link.com/tw/business-networking/omada-sdn-router/tl-r605/)。

## [repeater 中繼器](https://en.wikipedia.org/wiki/Repeater)

- 一個將輸入訊號增強放大的類比裝置。
- 中繼器是用來加強纜線上的訊號，把訊號送得更遠，以延展網路長度。
- 電子訊號在電纜上傳送時，訊號強度會隨著傳遞長度增加而遞減。
- 此需要中繼器訊號重新加強增加資料傳送距離。
- 一種用於頻率轉換及功率增強的模組或裝置，它分上行頻率和下行頻率，主要用於訊號增強和頻率差轉。
- [NETGEAR 中繼器](https://24h.pchome.com.tw/prod/DRAF4H-A900AVD0O)。

## [Hub 集線器](https://en.wikipedia.org/wiki/Ethernet_hub)

- 集線器相比交換機為簡單，被視為有多個埠的中繼器，一個埠接受位元位，其他埠送出。
- 它對實體層封包有所感知，檢測到其開始、掛起及衝突。
- 檢測到衝突時會傳送擁塞訊號以傳播這一事件。
- 集線器不能對經過的網路流量做進一步檢查與管理任何進入的封包都會被廣播到其他埠。
- 集線器無法儲存資料封包必須在接收時被傳送，旦發生衝突，就會丟包。
- 集線器只能半雙工模式工作。
- 衝突域更廣，相比於使用更複雜的網路裝置，使用集線器的資料網路更容易出現封包衝突。
- [Transcend 創見 集線器](https://24h.pchome.com.tw/prod/DGBN57-A900A6YJJ)。

## [Switch 交換器](https://zh.wikipedia.org/wiki/%E7%B6%B2%E8%B7%AF%E4%BA%A4%E6%8F%9B%E5%99%A8)

- 通過交換接收和轉發資料到目標裝置，能夠在電腦網路上連接不同裝置。
- 是一種多埠網橋，資料鏈路層使用MAC位址轉發資料。
- 通過引入路由功能，交換器也可在網路層轉發資料，這種交換器一般稱為三層交換器或多層交換器。
- 乙太網路交換器是網路交換器最常見形式。
- 繼器會在其所有通訊埠轉發相同資料，讓裝置自行判斷哪些是自己需要的資料，交換器則不然，它只會將資料轉發到需要接收裝置。
- [tp-link 交換器](https://24h.pchome.com.tw/prod/DRAN24-A900AN2CI)。


## [L3-Switch 交換器(ASIC)](https://zh.wikipedia.org/zh-tw/%E7%B6%B2%E8%B7%AF%E4%BA%A4%E6%8F%9B%E5%99%A8#%E4%B8%89%E5%B1%82)

- 可處理第三層網路層協定，用於連接不同網段，通過對預設閘道器的查詢來建立兩個網段間的直接連接。
- 可實現路由器全部或部分功能，但只能用於同一類型區域網路子網路之間互連。
- 可像二層交換器那樣通過MAC位址標識封包，也可以像傳統路由器那樣在兩個區域網路子網路之間進行功能較弱的路由轉發，路由轉發不是通過軟體來維護的路由表，而是通過專用的ASIC晶片處理這些轉發。

## [L4-Switch 交換器](https://zh.wikipedia.org/zh-tw/%E7%B6%B2%E8%B7%AF%E4%BA%A4%E6%8F%9B%E5%99%A8#%E5%9B%9B%E5%B1%A4)

- 可處理第四層傳輸層協定，可將對談與一個具體的IP位址繫結，以實現虛擬IP。

## [L7-Switch 交換器](https://zh.wikipedia.org/zh-tw/%E7%B6%B2%E8%B7%AF%E4%BA%A4%E6%8F%9B%E5%99%A8#%E4%B8%83%E5%B1%A4)。

- 充分利用頻寬資源來過濾，辨識和處理應用層資料轉換交換裝置。

