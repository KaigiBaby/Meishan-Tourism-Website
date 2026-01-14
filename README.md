# meishan-tourism-website
【梅．那麼簡單】嘉義縣梅山鄉旅遊網站，透過自身旅遊經驗，與更多人介紹嘉義之美。

國立嘉義大學資訊管理學系「網頁程式設計」課程的期末專題報告。
本網站旨在成為嘉義縣梅山鄉的數位名片，透過視覺化設計與豐富的互動功能，推廣梅山鄉獨特的自然美景（如雲海、步道、茶園）和在地文化。
不僅提供基本的景點介紹，更整合了主題導覽、自定義行程安排及交通方式等實用資訊，致力於成為一站式的梅山旅遊規劃平台。

# 網站主要功能
本網站提供以下核心功能，以提升使用者的旅遊規劃體驗：
1.互動式地圖：首頁包含梅山鄉互動式地圖，標示出實地走訪的景點。使用者可點擊地標連結到個別景點介紹頁面。
2.自訂行程與路線規劃：使用者可在景點頁面透過「儲存景點」按鈕將景點加入行程列表。在「自訂行程」頁面，結合 Google Maps API 實現路線規劃功能。提供開車、步行及騎車三種交通方式選擇。
3.景點收藏：使用者可將喜歡的景點加入收藏列表，方便快速查看感興趣的內容。
4.在地美食推薦：透過輪播美食照片，點擊圖片可查看店家資訊，並提供 Google Map 連結、美食部落格介紹及聯絡電話。
5.特別活動資訊：提供梅山鄉季節性或不定期的活動資訊，如：候鳥過境奇景、紫藤花季等。
6.即時資訊顯示：首頁顯示梅山鄉的即時天氣狀況、降雨機率和空氣品質 (AQI)。瀏覽人次紀錄 (Page Views)：網站底部利用 Firebase Realtime Database 紀錄並顯示網頁瀏覽人次。

# 開發工具與技術
本專案主要採用以下技術進行開發：
前端：Vue.js、Vuetify、HTML / CSS / JavaScript。
後端與資料庫：Firebase：用作後端服務與網站託管平台。
-Firebase Hosting：用於簡化 Web 應用和靜態網站的部署。
-Firebase Realtime Database：用於實時資料更新，如瀏覽人次紀錄。
整合服務：Google Maps API：用於實現自訂行程的路線規劃與地圖連結。

# 開發環境 (Development Environment)：Visual Studio Code 24。

# 安裝與啟動
本專案可透過梅山旅遊網站連結.txt中的網址連結瀏覽，但部分功能可能會無法正常顯示。
由於專案使用了 Vue.js/Vuetify，若要在本地啟動專案，需要 Node.js 環境。
1. 複製專案庫 Bash git clone https://github.com/KaigiBaby/meishan-tourism-website.git
2. cd meishan-tourism-website
3. 安裝依賴套件 (Install dependencies)請確保您已安裝 Node.js 和 npm。
4. 配置 Firebase (Firebase Configuration)若要確保網站功能（如瀏覽人次紀錄）正常運作，您需要配置您的 Firebase 專案金鑰。請在專案中找到 Firebase 設定檔案（通常是 .env 檔案或某個設定檔）。填入您的 Firebase Hosting 和 Realtime Database 相關配置資訊。
5. 執行專案啟動開發伺服器：Bash# npm run serve

# 專案團隊
本專案由國立嘉義大學資訊管理學系第九組成員共同完成(陳亭妃1114541 黃鈺婷1114544 蘇楷喆1114548 林葦翔1114549)。
指導教授：李彥賢 教授。
完成日期：中華民國 114 年 01 月 07 日。
專案維護：此網頁將交由組員黃鈺婷繼續更新維護。
