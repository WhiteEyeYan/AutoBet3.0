# AutoBet3.0  
語言：Java  
程式最後修改時間：2020/02/14  
效果展示：https://youtu.be/kmy4OCj03bg  
<br />  
使用Android SDK，在電腦上模擬Anroid系統
網頁端只有在下注時會有卡住問題  
數據獲取一樣可以使用selenium從網頁上獲取  
下注部分寫了一個類似按鍵精靈14的"區域找色"  
尋找特定顏色，決定是否有下注成功或是下注鈕是否是可按狀態  
點擊部分使用adb指令在特定座標上點擊及輸入數字  
  
點擊  
> adb -s 67ffc8bf shell input tap 540 990  

輸入  
> adb -s 67ffc8bf shell input text 100  
