# Sparkle Airline（後台.NET MVC 專案）


## 資展國際（原資策會）C#全端工程師養成班 FUEN31【第六組】

- **陳德奇（組長）、歐詩妤（技術長）、王學鈞、徐碩瑜、楊庭懿、文采姍、宗雋恩**
 <br> <br>
## 網頁架構與分工

### 【航空公司（主網站）】

- **歐詩妤**：班機動態、訂票、選位
- **王學鈞**：託運加購、會員哩程、機場管理
- **徐碩瑜**：飛機餐

### 【免稅商城（副網站）】

- **宗雋恩**：免稅商品管理、訂單結帳

### 【共用模組】

- **陳德奇**：會員系統、員工系統、權限系統
- **文采姍**：金流模組、班機介紹
- **楊庭懿**：優惠券、商品折扣

簡報內容：**Sparkle Air 期中專題.pdf** <br>
線上簡報：[線上簡報](https://www.canva.com/design/DAGC3LYsOMA/JWa3Fl-1UkpGkWKQi7mNJg/view?utm_content=DAGC3LYsOMA&utm_campaign=designshare&utm_medium=link&utm_source=editor)
 
 <br> <br>
## MVC架構（三層式架構）

### 【表現層】

- **SparkleAir.FrontEnd.Site**：MVC

### 【商業邏輯層】

- **SparkleAir.BLL.Service**：核心商業邏輯（Service）
- **SparkleAir.IDAL.IRepository**：資料存取層共用 Interface（IRepository）

### 【資料存取層】

- **SparkleAir.DAL.DapperRepository**：實作 IRepository，使用 Dapper 進行資料存取（Repository）
- **SparkleAir.DAL.DTORepository**：實作 IRepository，使用 DTO 進行資料存取（Repository）
- **SparkleAir.DAL.EFRepository**：實作 IRepository，使用 Entity Framework 進行資料存取（Repository）

### 【基礎建設層】

- **SparkleAir.Infa.Criteria**：搜尋方法用類別
- **SparkleAir.Infa.Dto**：Controller 與 Service 溝通用類別
- **SparkleAir.Infa.EFModel**：Entity Framework 存取資料庫用類別
- **SparkleAir.Infa.Entity**：Service 與 Repository 溝通用類別
- **SparkleAir.Infa.Utility**：公用程式、Helper、擴充方法
- **SparkleAir.Infa.ViewModel**：Views顯示類別
- <br><br>
  _本專題僅供資展國際專題發表使用，不涉及任何商業用途 如有侵權煩請告知_
