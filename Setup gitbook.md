#安裝 gitbook
1. 安裝[Node.js](https://nodejs.org/en/)<br>
1. 通過npm 來安裝gitbook，輸入安裝指令
```
npm install gitbook-cli -g
```
<img src="./images/Setup gitbook_001.jpg" alt="" height="300"  >

---------------------------------------
#基本使用
1. `gitbook init`安裝gitbook
>`README.md`和`SUMMARY.md`是兩個必須文件, `README.md`是對書籍的簡單介紹, `SUMMARY.md`是書籍的目錄結構
2. `gitbook serve`
>gitbook serve命令實際上會首先調用gitbook build編譯書籍，完成以後會打開一個web服務器，監聽在本地的4000端口

<img src="./images/Setup gitbook_002.jpg" alt="" height="200"  ><br>
* 本機預覽

<img src="./images/Setup gitbook_003.jpg" alt="" height="300"  >