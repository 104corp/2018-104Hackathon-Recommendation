| Name            | Description               | Comment                                                                     |
| :-------------: | :-----------------------: | :-------------------------------------------------------------------------: |
| action          | 瀏覽104時的行為記錄       | viewJob:瀏覽職務 applyJob:應徵職務 saveJob:儲存職務 (註1)                   |
| jobno           | 職務代碼                  | 被點擊的工作                                                                |
| date            | 此筆log的時間戳記         | unixtime(millisecond)                                                       |
| source          | 產品名稱                  | app / web / mobileWeb                                                       |
| device          | app裝置系統               | ios / android                                                               |


* 註1: train_click.json中的clickJob, clickSave, clickApply為網頁搜尋列表的點擊行為，train_action.json中的viewJob, saveJob, applyJob 包含網站上其他動線的行為(包含搜尋)
