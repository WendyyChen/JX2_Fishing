# JX3_Fishing
釣魚大概是最和平，也最無紛爭的一種活動。但它很無聊，所以想了一個辦法來解放雙手與時間。這裡使用的方法略為複雜，搭配了一些自動化測試工具、寫script還有巨集而達成自動釣魚的目的。看過坊間的一些按鍵精靈的自動釣魚script，並沒有很smart。希望這篇文章對大家都有幫助。

### Installation
以下是環境以及所需的工作安裝步驟，請按照順序完成。

#### Java(JRE):
若你的電腦沒有安裝Java環境，請先安裝Java(JRE即可)。到 [這裡](https://www.java.com/zh_TW/download/) 下載Java，請注意是 32bit/64bit 版本，務必要挑對符合你電腦的版本，若實在不知道自己的電腦是32bit/64bit，就請身旁熟悉而且可以信任的朋友解答一下。安裝Java很簡單，基本上就是next/next/finish的概念。

#### Sikuli
這是一套以圖形比對的自動化測試工具，你可以在 [這裡](https://launchpad.net/sikuli/+download)下載sikulixsetup-1.1.0.jar ，有安裝好Java的話，基本上也是雙點之後就自動會解壓安裝好。若真的不習慣官方網站這樣的安裝方式，這裡也可以直接下載，解壓縮後，就完成了。

### How to use
安裝完後，會出現下列的資料夾，以 “系統管理員” 的身份執行 `runSukuli.bat` ，如下圖:

[圖]

執行後，會看到程式畫面。
「圖」
來對Sikuli 多做一點說明。Sikuli使用的是 python 語法。建議還是熟悉一下它的語法比較好，這樣比較容易瞭解這些script是在寫什麼。
