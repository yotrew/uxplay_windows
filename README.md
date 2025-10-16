# AirPlay on Windows  
## 將iPhone/iPad畫面投影在Windows上  
這是使用https://github.com/antimof/UxPlay 來建立uxplay windows版  
原本在網路上就有https://github.com/leapbtw/uxplay-windows/  
但有人覺得它有病毒(但它是公開在github且有source code,  
要使用uxplay時要把它加入防火牆白名單,因為它是網路服務,有沒有毒自己check吧!)  
又搬出"授人以魚不如授人以漁"來說教  
而我的想法是今天若只是為了將iPhone/iPad畫面投影在Windows上而已,有必要裝個MSYS2及gcc等toolchain嗎?  
為了投影要在電腦先裝個**3GB**左右的檔案,有必要嗎?  
如果你想要了解人家怎麼寫或是研究它，我覺得動手自己做是一件很好的是  
但如果要我要在5X個班級電腦上裝上投影程式，有必要這樣嗎從頭自己做嗎?  
所以我就從頭把它編成Windows可執行檔，並把必要檔案收集在同一目錄中，  
讓它變成綠色軟體…  
uxplay1.72.zip(https://github.com/yotrew/uxplay_windows/raw/refs/heads/main/uxplay1.72.zip)  
MD5:0A82BCF1B355338817688DEC0E915BE7  
1.直接下載uxplay1.72.zip,解壓縮  
2.進uxplay,安裝Bonjour.msi或Bonjour64.msi  
3.將uxplay.exe加入防火牆中的"允許程式通過防火牆"  
4.執行uxplay.exe  
5.開啟iPhone/iPad投影->選"UxPlay@你的電腦名稱"  