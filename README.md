# 歡迎使用 Han Count !

這是紀錄某新聞台提到有關`"韓"`的次數的紀錄程式，由nodejs + gcp編寫而成。

身為高雄北漂工程師，響應韓總發財政策，決定用程式碼協助追隨韓總腳步。

以下網站會追蹤韓總新聞台提到韓總的次數，並即時顯示在畫面上。

[韓總計數器](http://35.199.161.19/)

## 如何開始

1. 把 `_env.js` 更改成 `env.js`。

2. 更改`env.js`設定

3. 輸入 `npm install`

4. 運行 `node .`，如果執行失敗再`npm install`一次。

## QA

Q:可以計算其他新聞台和關鍵字嗎？<br>
A:當然可以，但我是沒錢仔只有免費專案的VM，跑韓總就很吃力了，不過還是有解決方案，就是強行開源，要追蹤功德兄什麼的就交給你們了。

Q:資料會存下來嗎？可以查找嗎？<br>
A:不會，我是沒錢仔，DB很貴，嗚嗚，好想發大財。

Q:語音判斷會重複和漏掉某些段落能解決嗎？<br>
A:能，但我不能，技術不夠，求大神幫助看看源碼要怎麼修正。

Q:字幕一直出現同音不同字的狀況正常嗎？<br>
A:語音辨識是使用gcp的speech，跪求大神提出解決方案。

Q:網站會開到什麼時候？<br>
A:直到GCP免費專案沒錢為止。