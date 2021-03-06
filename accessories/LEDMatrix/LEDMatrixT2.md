# 流光溢彩屏教程（中）

本教程將會教大家使用neomatrix插件對溢彩屏進行編程。

## 接線

溢彩屏需要配合robotbit使用，請如圖將屏幕與robotbit接線。

![](./LEDMatrixT1/ggg.jpg)


## Makecode編程教學（只限離線版makecode）

![](./images/mcbanner.png)

假如我們想顯示文字或圖形，使用neopixel實在太麻煩了，有見及此kittenbot推出了neomatrix插件，容許圖像化的圖案編輯。

#### (注意，本插件只支援離線版makecode)
 
### 1.加載neomatrix插件

neomatrix插件: https://github.com/KittenBot/pxt-neomatrix

![](./LEDMatrixT1/2.png) 

![](./LEDMatrixT2/ext.png) 

### neomatrix積木塊:

![](./LEDMatrixT2/blocks.png)

    注意：現階段溢彩屏並不兼容powerbrick！請使用robotbit！
    PowerBrick只支援套件中的全彩點陣屏。

### 2.點擊NeoMatrix Editor進入編輯器

![](./LEDMatrixT2/edit.png)

首先選擇溢光屏類型（16x16/8x32）

![](./LEDMatrixT2/editor1.png)

我們亦可以在文字欄輸入文字，按Render生成圖案。

![](./LEDMatrix/hello.png)

可以在黑色像素格上點擊，畫出你想要的圖案。（單擊填色，雙擊清除）

![](./LEDMatrixT2/editor2.png)

我們可以按Add Frame增加一幀。

![](./LEDMatrixT2/editor3.png)

我們亦可以按Open Image直接生成圖案。

![](./LEDMatrix/bianjiqi4.png)

![](./LEDMatrix/glasses.png)

完成後在Output欄中點擊Matrix Panel，生成積木。

![](./LEDMatrixT2/editor4.png)

返回makecode主介面後我們可以看到NeoMatrix中新增了一塊叫Show Frame的積木。

![](./LEDMatrixT2/editor5.png)

### 3.編寫程式

![](./LEDMatrixT2/image4144.png)

    用PowerBrick套件中的全彩點陣屏請使用PowerBrick積木。

[參考程式下載](https://bit.ly/LEDMatrixT2_01Hex)

## 流水式走字效果(32x8)

neomatrix亦都支援流水式走字的動畫。

![](./LEDMatrixT2/image4145.png)

[參考程式下載](https://bit.ly/LEDMatrixT2_02Hex)

    注意：現階段只支援8x32溢光屏走字。
    16x16的走字請參考《流光溢彩屏進階教程》。

## 插件版本與更新

插件可能會不定時推出更新，改進功能。亦有時候我們可能需要轉用舊版插件才可使用某些功能。

詳情請參考: [Makecode插件版本更換](../../../Makecode/makecode_extensionUpdate)

## FAQ

問：為什麼我點亮燈板的時候，燈板未能顯示我定下的顏色，燈板只點亮了紅色？

答：電源不足夠。

解決方法：將robotbit的電源打開，或者在供電轉接板加插外部電源（支援USB或5V火牛）。

## 注意事項
- 請勿接駁電壓高於5V的電源。
- 長時間使用請接駁外部電源。
- 本產品只適合14歲以上的兒童獨立使用，8-14歲兒童請在成年人的陪同下使用。
- 使用前請參考Kittenbot官方資料，不要隨便接駁電路，請勿外接大電流電機舵機。
- 請勿在金屬表面或導電性物料上使用，以免短路。
- 請勿在有水或潮濕的地方使用，以免短路。
- 請勿用手觸碰燈板外露的電線。