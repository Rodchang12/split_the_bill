# split_the_bill

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# split_the_bill

1.創建活動分帳群組，每個成員都能共同編輯並顯示建立及修改人。
  - 主頁面:
    - 活動標題: 置頂
    - 群組成員: icon、名字、分享共編連結
    - 帳單數目: 數字
    - 近期變動: 顯示建立人、修改時間、修改紀錄、刪除紀錄
    - 花費欄(nav): 群組花費、個人花費、代收付款項
    - 款項清單:
      - 合計金額
      - 第幾天、日期時間、地點、品項、金額
    - 新增款項按鈕: 捷徑按鈕、固定在網頁右下角、連結帳目頁面

2.帳目頁面包含:分類、標題、日期、金額、支付人、付款人、結帳、註解。
  -帳目頁面
    - 分類: icon、下拉式選單
    - 標題: 輸入框
    - 日期: 下拉式選單、年月日、時間、輸入框(非必要)
    - 金額: 幣別、icon、輸入框
    - 地點: 下拉式選單、輸入框
    - 付款人: 群組成員、下拉式選單、複選按鈕
    - 還款人: 群組成員、下拉式選單、複選按鈕
    - 結帳: 顯示尚未結帳及結帳成員
    - 註解: 輸入框、圖片上傳 


3.計算平均及總花費，並指定群組中特定成員進行分帳，根據收支算出最少轉帳次數。
  - 計算功能: 加總花費、攤銷數目
  - 帳款圖表化: 長條圖、圓餅圖
