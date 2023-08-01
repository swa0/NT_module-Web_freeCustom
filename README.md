# NT_module-Web_freeCustom

NT模板客製化版本

## 說明

此版本是基於 **NT3** 而製作的模板，用途: 客戶想要走自己的規則，給客戶做客製的預覽模板。</br>
如果客戶不採用 <a href="https://github.com/swa0/NT_module-Web_colorSystem">我們配色的版本</a>，</br>
就是要複製這個專案的分支 (空檔，不含預覽功能) **進行修改色系，再打包給後端。**

## 檔案結構(目錄結構)

|--- /css</br>
|--- /html  ```已登入網頁資料夾```</br>
|--- /img ```圖片資料夾```</br>
│&nbsp;&nbsp;&nbsp;&nbsp;├── enter   ```遊戲入口圖資料夾```   
│&nbsp;&nbsp;&nbsp;&nbsp;├── icon   ```icon資料夾```   
│&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp; ├── svg   ```svg資料夾```</br>
│&nbsp;&nbsp;&nbsp;&nbsp;├── partner   ```遊戲類別資料夾```   
│&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp; ├── XXX(遊戲類別名)</br>
│&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp; │&nbsp;&nbsp;&nbsp;&nbsp; ├── ```內頁遊戲大圖(遊戲類別BG_)/內頁遊戲廠商按鈕(遊戲類別Btn_)/該類別遊戲廠商下拉選單圖```</br>
|--- /js ```JS資料夾```</br>
│&nbsp;&nbsp;&nbsp;&nbsp;  ├── javascript.js ```JS資料夾(功能)```</br>
|--- /scss ```scss樣式資料夾```</br>
│&nbsp;&nbsp;&nbsp;&nbsp;  ├── _colorStyle.scss ```原有的顏色規則``` </br>
│&nbsp;&nbsp;&nbsp;&nbsp;  ├── _editColor.scss  ```後天的客製顏色規則(已編輯變數)```</br>
│&nbsp;&nbsp;&nbsp;&nbsp;  ├── _imgStyle.scss ```圖片(背景圖)路徑```</br>
│&nbsp;&nbsp;&nbsp;&nbsp;  ├── _jumpWindow.scss ```內涵蓋客製化控制彈窗``` </br>
│&nbsp;&nbsp;&nbsp;&nbsp;  ├── _aside.scss ```內涵蓋側邊控制項``` </br>
│&nbsp;&nbsp;&nbsp;&nbsp;  ├── ... ```以上僅列出需要特別注意的資料夾``` </br>
|-- index.html ```首頁(未登入)```</br>


## 針對各個Scss檔案的詳細說明

- ***_colorStyle.scss*** ```原有的顏色規則```</br>


- ***_editColor.scss*** ```後天的客製顏色規則(已編輯變數)```</br>


- ***_imgStyle.scss*** ```圖片(背景圖)路徑```</br>


- ***_jumpWindow.scss ***  ```內涵蓋客製化控制彈窗```</br>

    ```.quickBtnStyleEditr``` 快速按鈕彈窗</br>

    ```.buttonEdit``` 客製化按鈕彈窗</br>

- ***_aside.scss *** ```內涵蓋側邊控制項```</br>

    ```.colorSelector``` 此為控制顏色面板

