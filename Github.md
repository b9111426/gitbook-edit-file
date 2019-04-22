# Github

<table><td bgcolor=#5ca0d3><font size="6">上傳步驟</td><table>
<img src="./images/Github_001.jpg" alt=""><br>

1. **增加全部檔案進入索引**
```
git add .
```
2. **將索引提交到數據庫**
```
git commit -m '更新訊息'
```
3. **上傳遠端**
```
git push
```

<table><td bgcolor=#5ca0d3><font size="6">刪除檔案</td><table>

1. 指定的目錄下所有的檔案從索引或本地數據庫移除
```
git rm --cached -r .
```
2. 強制清除未加入版控的資料
```
git clean -df
```
3. 強制刪除指定的目錄下所有的檔案
```
rm -rf *~
```
<br>

>-d：直接刪除一個目錄，既使目錄不是空的<br>
>-f：--force 就是強制刪除檔案或目錄<br>
>-r, -R：將指定的目錄下所有的檔案與子目錄一併處理