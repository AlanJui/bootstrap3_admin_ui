# 專案摘要

以 CMS 後台管理操作介面為題，學習 BootStarp 3（V3.3.7） 之引用。

為了能立即觀察 HTML, CSS 的輸出結果，本專案特地引用 [Yemoan Genator： WebApp](https://github.com/yeoman/generator-webapp#readme) 
，做為開發工具，以便在練習的過程中，可以隨時透過眼視的方式，驗證事情是否做對。

所以，請依據如下「開發工具」所述，先在電腦中備妥所需使用之「工具軟體」：  　

### 開發工具： 
 
 - NodeJS ： 9.3.0
 - NPM: 5.6.0
 - Bower: 1.8.2
  

# 操作指引

## 瀏覽成果

想要立即知道「輸出結果」為何，請依如下步驟操作：

 1. 打開「終端機」，先進入專案所在目錄路徑。然後，輸入下列指令：
 
 ```
 $ cd <專案所在目錄路徑>
 $ gulp serve
 ```
 
 2. 在 Web 瀏覽器，觀看輸出結果。
 
 ```
 http://localhost:9000/
 ```

## 跟著練習

想跟著【參考來源】所述之教學影片，來段「做中學」的學習過程，請依如下步驟操作：

 1. 打開自己喜歡的「程式碼編輯器」。
 
 2. 將 index-init.html 檔案中的內容抄入 index.html 檔案中。
 
    【附註】：上述之檔案，置於「目錄： app 」之中。
 
 3. 執行上述「瀏覽成果」的兩道操作步驟。
 
 4. 播放教學影片，跟著講師的示範，在「程式碼編輯器」進行練習。

    【附註】： 因為受限於開發工具的規範，教學影片中講師的專案目錄、檔案結構，在此處有了一番調整：
    
      (a) 教學影片中 .html 檔案，原本均放在專案的根目錄之中；在本專案需改放在「目錄： app 」之中；
      
      (b) 教學影片中 .css 檔案，原本均放在專案根目錄下的 `css` 目錄之中；在本專案變更如下：
          
          - bootstrap.min.css 檔案：置於 `bower_components/bootstrap/...` 目錄之中 
      
          - style.css 檔案：檔名改成 main.css ，存檔的目錄路徑改置於 `app/sytles/` 目錄之中

 
# 【參考來源】

 - 教學影片：[Build A CMS Admin Bootstrap Theme From Scratch](https://www.youtube.com/watch?v=pXbEcGUtHgo)
