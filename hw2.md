
### PERT圖



### 甘特圖

```mermaid
gantt
    title A Gantt Diagram
    研擬計畫    :a1, 2023-10-02, 1d
    任務分配    :a4, after a1  , 4d
    取得硬體    :after a1  , 17d
    程式開發    :2023-10-04  , 70d
    安裝硬體    :2023-10-05  , 10d
    程式測試    :2023-10-06  , 30d
    撰寫使用手冊    :after a4  , 25d
    轉換檔案    :after a4  , 20d
    系統測試    :2023-10-08  , 25d
    使用者訓練    :2023-10-09  , 20d
    使用者測試    :2023-10-11  , 25d
```

```mermaid
gantt
    title 任務分配

    section 1
    研礙計畫     :a1, 2023-10-02, 1d
    section 2
    任務分配     :after a1  , 4d
    section 3
    取得硬體     :after a1  , 17d
    section 4
    程式開發     :a4, 2023-10-7  , 70d
    section 5
    安裝硬體     :a5, 2023-10-19   ,10d
    section 6
    程式測試     :a6, after a4   ,4d
    section 7
    撰寫使用手冊     :a7, after a5 ,25d
    section 8
    轉換檔案    :after a5  , 20d
    section 9
    系統測試     :a9,after a6 , 25d
    section 10
    使用者訓練    :a10, after a7 , 20d
    section 11
    使用者測試    :after a9 , 25d
