## description
這個特效是一個fade效果，所以第一個想法就是改變它的透明度，透明度在css中可以用opacity來設定，接著它在淡出期間會下降，所以也要調整與上邊的距離，在css中也就是改變margin-top
知道要修改那些css屬性後，接著就是選擇一種方法來完成動畫的部分，範例有三種作法，分別是css transition屬性, jQuery animation, 以及semantic ui的transition api
