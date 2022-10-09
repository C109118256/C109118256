```mermaid
gantt
    title 甘特圖

    section Section
    研擬計畫           :a1, 2022-11-04, 1d
    任務分配           :after a1  , 4d
    程式開發           :a2, after a1  , 70d
    程式設置           :a4, after a2  , 30d
    系統設置           :a8, after a4  , 25d
    使用者設置         :after a8      , 25d
    section Another
    取得硬體           :a3, after a1  , 17d
    安裝硬體           :a5, after a3  , 10d
    撰寫使用手冊       :a7, after a5  , 25d
    轉換檔案           :after a5     , 20d
    使用者訓練         :after a7     , 20d
```
