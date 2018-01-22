* 把css *所有元素都設 box-sizing: border-box;  
background-size  可以設 cover。會自動填滿所有圖片。  
background-position 請設 "center center"  

* font-size使用vmin，如果螢幕變小，字也會跟著縮小。那些margin、line-height等也都用vmin ，這樣很棒。  

* 防止文字溢出：(模版)  
在最接近文字的html元素，設
overflow: hidden, text-overflow: ellipsis; 