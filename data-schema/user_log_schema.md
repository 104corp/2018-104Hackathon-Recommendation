| Name            | Description               | Comment                                                                                                                                               |
| :-------------: | :-----------------------: | :-------------------------------------------------------------------:                                                                                 |
| action          | 瀏覽104時的行為記錄       | clickJob:點擊職務 clickSave:點擊儲存 clickApply:點擊應徵 viewJoblist:看工作列表 viewJob:瀏覽職務 applyJob:應徵職務 saveJob:儲存職務 viewCust:瀏覽公司 |
| jobNo           | 職務代碼                  | 被點擊的工作 (viewJoblist無此欄位)                                                                                                                    |
| date            | 此筆log的時間戳記         | unixtime(millisecond)                                                                                                                                 |
| joblist         | 工作列表                  | 以","為分隔的工作列表 (viewJob, saveJob, applyJob, viewCust無此欄位)                                                                                  |
| querystring     | 網址參數                  | 載入工作列表的網址參數 (viewJob, saveJob, applyJob, viewCust無此欄位)                                                                                 |

* 註:1 網址參數說明

  + area: 地區
  + asc: 排序
  + dep: 科系
  + dis_role: 身障
  + edu: 學歷
  + excludeCompanyByCustno: 以公司代碼排除公司
  + excludeCompanyKeyword: 以關鍵字排除公司
  + excludeIndustryCat: 排除產業
  + excludeJobKeyword: 排除職務
  + expcat: 經歷要求
  + indcat: 產業
  + isnew: 工作更新日
  + jobcat: 職務類別
  + jobexp: 經歷要求
  + jobsource: 產品
  + keyword: 關鍵字
  + kwop: 只搜尋職務名稱
  + lang: 語言
  + mode: 顯示模式
  + order: 相關性排序
  + page: 頁碼
  + ro: 身份
  + rostatus: 身份類型
  + s5: 輪班
  + s9: 上班時段
  + sr: 是否有寫薪資
  + scmax: 薪資條件上限
  + scmin: 薪資條件下限
  + wf: 福利
  + wt: 工讀性質
  + wktm: 休假制度
  + zone: 科技園區
