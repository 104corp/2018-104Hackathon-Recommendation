| Name            | Description               | Comment                                                                                                                                     |
| :-------------: | :-----------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: |
| action          | 瀏覽104時的行為記錄       | clickJob:點擊列表職務 clickSave:點擊列表儲存 clickApply:點擊列表應徵 viewJob:瀏覽職務 applyJob:應徵職務 saveJob:儲存職務 (註1)              |
| jobno           | 職務代碼                  | 被點擊的工作                                                                                                                                |
| date            | 此筆log的時間戳記         | unixtime(millisecond)                                                                                                                       |
| joblist         | 工作列表                  | 以","為分隔的工作列表 (viewJob, saveJob, applyJob 無此欄位)                                                                                 |
| querystring     | 網址參數                  | 載入工作列表的網址參數(註1) (viewJob, saveJob, applyJob 無此欄位)                                                                           | 
| source          | 產品名稱                  | app / web / mobileWeb (clickJob, clickSave, clickApply的來源皆為web)                                                                        | 
| device          | app裝置系統               | ios / android (clickJob, clickSave, clickApply的來源皆為web，因此無此欄位)                                                                  | 


* 註1: clickJob, clickSave, clickApply為網頁搜尋列表的點擊行為，viewJob, saveJob, applyJob 是網站上其他動線的行為(包含搜尋)
* 註2: 網址參數說明

  + area: 地區
  + asc: 排序 (0:降冪, 1:升冪)
  + dep: 科系
  + dis_role: 接受身障 (99:是)
  + edu: 學歷 (1:高中職以下 2:高中職 3:專科 4:大學 5:碩士 6:博士)
  + excludeCompanyKeyword: 以關鍵字排除公司
  + excludeIndustryCat: 排除產業
  + excludeJobKeyword: 排除職務
  + expcat: 經歷要求
  + indcat: 產業
  + isnew: 工作更新日 (0:本日最新, 3:三日內, 7:一週內, 14:二週內, 30:一個月內)
  + jobcat / cat: 職務類別
  + jobexp: 經歷要求
  + jobsource: 產品
  + keyword: 關鍵字 
  + kwop: 只搜尋職務名稱 (1:是, 7:否)
  + lang: 語言
  + m: 手機使用電腦版網頁 (1:是)
  + mode: 顯示模式 (l:列表, s:摘要)
  + order: 相關性排序 (1:相關性排序, 2:日期排序, 3:經歷, 4:學歷, 7:應徵人數)
  + ro: 身份 (0:全部, 1:全職, 2:兼職, 3:高階, 4:派遣, 5:接案, 6:家教)
  + rostatus: 身份類型 (1024:學生實習, 2048:二度就業, 16:研替)
  + s5: 輪班 (0:不須輪班, 256:輪班)
  + s9: 上班時段 (1:日班, 2:晚班, 4:大夜班, 8:假日班)
  + sctp: 薪資計算 (P:時薪, S:月薪)
  + sr: 是否有寫薪資 (99:是)
  + scmax: 薪資條件上限
  + scmin: 薪資條件下限
  + wf: 福利 (1:年終獎金, 2:三節獎金/禮品, 3:員工旅遊, 4:分紅配股, 5:設施類福利, 6:休假福利, 7:津貼補助, 8:彈性上下班, 9:健康檢查, 10:團體保險)
  + wt: 工讀性質 (1:長期工讀, 2:短期工讀, 4:假日工讀, 8:寒假工讀, 16:暑期工讀)
  + wktm: 休假制度 (1:週休二日, 2:隔週休)
  + zone: 科技園區 (1:竹科, 2:南科, 19:內湖, 20:南港, 21:中科, 64:外商, 16777216:中科(與21同), 4194304:內湖(與19同), 8388608:南港(與20同))
